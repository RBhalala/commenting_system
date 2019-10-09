# commenting_system
Commenting system like Hacker News using socket

it will install and configure the following:

* Mongo
* Node
* EJS
* Express

## Prerequisities
  To install Mongo DB use https://docs.mongodb.com/manual/administration/install-community/ 
  
  Start your Mongo server , Run below command to start the Mongo server:
  ```shell
  sudo service mongod start
  ```
### Create database and collections
  ```shell
  use commenting_system
  
  db.createCollection("posts")
  db.createCollection("comments")
  db.createCollection("users")
  ```
  
## Running the installer

  ### The following commands must be executed in your local machine

  Clone commenting_system with HTTP or download the project:
  ```shell
     $ git clone https://github.com/RBhalala/commenting_system.git
  ```
  
  ### install all the required package
  - Using npm
  ```shell
     $ npm install
  ```
  ### Run project using below command
  ```shell
     $ node app.js
  ```
