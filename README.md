# docker-compose
This is a docker-compose infrastructure program to solve the problem of management in our day to day life.
# Problem:- To start any service we have to do lots of code and envirnment setup but my using docker-compose we can setup it as like when             we start our OS/container the service/application starts.
# Solution:-
*Infrastructure as a code* :- i am creating these set of codes where everything is pre-defined for your service to start.
# steps: 
1) download docker in your base OS(linux) and enable its services.
2) Download the image of particular OS regarding your project/service such as wordpress and mysql images to start wordpress site service.
   Cmd for linux base OS : Docker pull wordpress:latest or docker pull wordpress:5.1.1-php7.3-apache
                           Docker pull mysql:latest or  Docker pull mysql:5.7
   Docker have its own cmd for downloading any iso file.
3) Then Download Docker-compose to setup your infrastructure:-

   Run the following cmds for the same :
   
*curl -L https://github.com/docker/compose/releases/download/1.25.4/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose

   *chmod +x /usr/local/bin/docker-compose

4) make a file with Docker-compose.yml name and copy the code from my repository to this file and your job is done.
