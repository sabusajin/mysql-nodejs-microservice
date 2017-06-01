# mysql-nodejs-microservice

Build a microservice using Node.js and Docker with a MySQL backend!

**Prerequisites**
Docker [Install Docker](https://docs.docker.com/engine/installation/)
Docker Compose [Install Docker Compose](https://docs.docker.com/compose/install/)


**Instructions**
To build the project, navigate in terminal to the folder with docker-compose.yml file.
	
    Once there, type the following command-
    
    > docker-compose build
    > docker-compose up
    
These commands will create two containers, one running test-database microservice (MySQL) and the other running users-service microservice (Node.js)

You can view the database user using http://localhost:8123/users

If you are using docker-machine, you may need to use the IP address of the docker machine.

Find that using -
	> docker-machine ls

Then, you can use that IP address of the docker-machine to see the database!
Use https://ip-address-of-docker-machine:8123/users


