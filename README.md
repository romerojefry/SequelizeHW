# SequelizeHW

## Description 
This application is a sign up and log in form where the user has the option to sign up or sign in if they have an account. Once they are logged in, it displays their email and the option to log out. 
 

## Table of contents 

* [Title](#Title)
* [Description](#Description)
* [license](#License)
* [Installation](#Installation)
* [Usage](#Usage)
* [Test](#Test) 
* [Contributing](#Contributing)
* [Questions](#Questions)

## Installation
npm install 
npm init -y
npm express 
npm mysq12 sequailize 
Bcrypt.js

## Usage
** FILES WALKTHROUGH **
Config file
-middleware
Its a javascript file where restricts routes if the user isn't logged in
-Config.json
This file configuration connects to the server and MySql
-Passport.js
This file authorizes requests for the user password and email

Models files
-Index.js
This file creates database structures from sequalize
-User.js
This file checks if the match account is connected to the user input adn sercures the password

Public files
-JS
The javascript is function is logging in and inputs when the users logs in and get request when user is making an account
-HTML
styling of the website display and buttons that fire the functions

Rotes file
-api.js
this contains the routs of call back function from the user input which goes through app.post and app.get
-html.js
The file function is to know if the user is logged in and directs them into the correct html

Package.json
This JSON contains the node modules being use

Server.js
This file is where the port is connecting to the server and mysql through node.js and the installation of npms




##Contribing 
None

## License 
MIT

## Test
node index.js

##Questions
None