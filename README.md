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


##Contribing 
None

## License 
MIT

## Test
node index.js

##Questions
None