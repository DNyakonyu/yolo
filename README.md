# Nodejs, Express API and MongoDB e-commerce feature project

## Author-Duncan Ndirangu


## Requirements
Make sure that you have the following installed:
- [node](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04) 
- npm 
- [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) and start the mongodb service with `sudo service mongod start`

## Navigate to the Client Folder 
 `cd client`

## Run the folllowing command to install the dependencies 
 `npm install`

## Run the folllowing to start the app
 `npm start`

## Open a new terminal and run the same commands in the backend folder
 `cd ../backend`

 `npm install`

 `npm start`

## About the app
Actually, there are two separated apps. The Client which serves the FrontEnd (using React), and the Backend (in Node/Express).

Run the app using :
`$ docker-compose up --build`

![Image Source: [Google Images](https://sujaykundu.com/building-mern-apps-using-docker)](https://cdn-images-1.medium.com/max/2000/1*JJFt8gRBPBCjSwNYqhP3UA.png)


To check the status :
### MongoDB: A cross-platform document database

`docker-compose ps`
[MongoDB](https://www.mongodb.com/) is a NoSQL (non-relational) document-oriented database. Data is stored in flexible documents with a JSON (JavaScript Object Notation)-based query language. MongoDB is known for being flexible and easy to scale.

### How to stop the App :
### Express: A back-end web application framework

`$ docker-compose stop`
[Express](https://expressjs.com/) is a web application framework for Node.js, another MERN component. Instead of writing full web server code by hand on Node.js directly, developers use Express to simplify the task of writing server code.

## Languages & tools
### React: A JavaScript library for building user interfaces

- [Node](https://nodejs.org/en/)
[React](https://reactjs.org/) was originally created by a software engineer at Facebook, and was later open-sourced. The React library can be used for creating views rendered in HTML. In a way, it’s the defining feature of the stack.

- [Express](https://expressjs.com/)
### Node.js: A cross-platform JavaScript runtime environment

## Creating the Build

#### To create the build for the entire application, we need to run the following command: docker-compose build 

## Starting the Services

#### We can start the multi-container system using the following simple command: docker-compose up
#### At last, we can open http://localhost:3000 to see our React Frontend.
#### The backend server is live on http://localhost:5000
#### And MongoDB is running on http://localhost:27017


### License MIT

