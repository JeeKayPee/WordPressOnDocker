# Wordpress on Docker. 

This guide explains how to run Wordpress on Docker. 

Run the following commands on the terminal

docker pull wordpress

docker pull mysql:5.7

In the folder where stack.yml is stored, run the following command
docker-compose -f stack.yml up


wait for it to initialize completely, 

 http://localhost:8080



git clone https://github.com/JeeKayPee/WordPressOnDocker.git
cd WordPressOnDocker
sh deploy.sh
