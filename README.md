# Creating Full-Stack MERN App with Docker
- This repository is created through learning docker
- Please feel free to clone it and enjoy learning as well.
.

## About the app
Actually, there are two separated apps. The Client which serves the FrontEnd (using React), and the API (in Node/Express) as well as MongoDB for the Database.

## How to run the API
1. In your terminal, navigate to the `api` directory.
2. Run `npm install` to install all dependencies.
3. Run `npm start` to start the app.

## How to run the Client
1. In another terminal, navigate to the `client` directory.
2. Run `npm install` to install all dependencies.
3. Run `npm start` to start the app

## Check if they are connected
1. With the two apps running, open your browser in http://localhost:3000/.
2. If you see a webpage saying `Welcome to React`, it means the FrontEnd is working.
3. If the same webpage has the phrase `API is working properly`, it means the API is working.
4. If the same webpage has the phrase `Connected to Database`, it means the Database is connected and it is working. 

## ALERT
1. To connect with Mongodb database you need to run your mongodb locally.

## Ready for Docker!
1. Run `docker-compose build` .
2. Run `docker-compose up` .
3. I use Docker Toolbox therefore, to check the app, i need to go to `http://192.168.99.100:3000` . it all depends on your api address.


