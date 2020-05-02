# project1

Docker Compose is a complementary system which helps you link together individual Docker containers so they can work together. This guide walks through the deployment of a WordPress container and another MySQL container that WordPress will use to store its data. Docker Compose will facilitate the networking between them.

About the project:- 
I have used docker compose to host wordpress in order to create an app. WordPress is a free and open-source content management system written in PHP and paired with a MySQL or MariaDB database. Also I am using MYSQL database to store information.This type of architecture is known as multi-tier architecture.

I will be downloading the images of wordpress and mysql from the docker hub using the pull command.
Then we are supposed to launch both the containers using the specified images of Wordpress and Mysql respectively.
Then we need to download docker compose
I will be creating a directory under docker compose and creating a file in the directory docker-compose.yml and in the file we will be writing the code.
In the code we are using various commands to:- a) To create our own storage (volume):- So that our data is not lost whenever our container is deleted. b) Linking wordpress to the mysql database c) Passing the value of variables in wordpress and mysql.
