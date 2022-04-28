# ECE5710DataCenterProject
ECE5710 Project with two microservices applications communicate with each other by RabbitMQ
## First thing first
For the two microservices admin/main
use `docker-compose up` command run the applications
**Note**: if it is the first time you run it, you should choose the first command in [docker-compose](https://github.com/walliampeace/ECE5710DataCenterProject/blob/main/python-microservices/admin/docker-compose.yml) file 
and main app [docker-compose](https://github.com/walliampeace/ECE5710DataCenterProject/blob/main/python-microservices/main/docker-compose.yml) file to create database and migrate database
after that you can change these two files and change it to regular run command without migrating database
## Second
move to the react folder
use `npm install` and `npm start` to start the front-end page
## Third
If you want to use like api, you should first create several users from postman website,
you should enter the http://localhost:8000/api/user as the request URL and choose the **Post** to create users.
Then you can like the pictures and the other app can update likes.
