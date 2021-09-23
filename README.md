# Earth Best Revature Social Network

## Description
In this social network, everyone is friends with everyone. As a user, you will be able to register and login to your account. When you successfully login, you are automatically friends with everyone which means you will see a feed of everyone's posts. Users will be able to create a post and like other people's posts. Users will also have the ability to view other profiles which will display posts of that specific user.

## Technologies
* Apache Tomcat
* Spring Boot
* Spring Data
* Spring MVC
* Docker
* Bootstrap
* Servlet
* Jackson Databind
* Bcrypt
* Junit
* Log4j
* JavaMail
* PostgreSQL
* Mockito
* Sonar Cloud
* Angular 2+
* H2
* Jasmine
* AWS S3
* AWS EC2
* AWS RDS

## Features
* Users can: register, login, logout, reset password using email
* After login, users can: 
  - Modify their information, search for other people, view another people's profile
  - Create a post (with image and YouTube video), comment a post, like a post, view all the posts
  - Receive the notification when someone like or comment your post


## Getting Started
### Backend
Environment Variable:
* DATABASE_URL: URI to the databse
* S3ACCESS: AWS S3 access key
* S3SECRET: AWS S3 secret key
* EMAIL_PASSWORD: email app password for sending email
To create the docker image, run the following command:
~~~~
mvn clean package
docker build -t [IMAGE_NAME] .
~~~~

### Frontend
To create the docker image, run the following command:
~~~~
npm install
ng build
docker build -t [IMAGE_NAME] .
~~~~

## Contributor
* Zimi Li: <zimi.li@revature.net>
* Andrew Patrick
* Kevin Dian
* Bhavani Yelagala
