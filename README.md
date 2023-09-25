# ecomBackend
# Ecommerce Backend
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Description
  This project was about building out the backend of an ecommerce platform. The goal of the project was to learn how to use object relational mapping. I used Sequelize, which is a javascript ORM tool. I created models which map to a sql database and write the sequel dynamically as the routes are hit. This project was tough for me but definitely a good learning experience. There is a video demonstrating functionality and it can be found [Here](https://youtu.be/iofzNsaZUqw)


  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Credits](#credits)
  - [Tests](#tests)
  - [Questions](#questions)

  ## Installation
  To install this, clone the repo onto your local machine, and install the dependencies by running npm i in your command line.
  ## Usage 
  To use this you have to source the database. Make sure you are using the correct database (ecommerce_db). To source the database make sure you are in the ecomBackend directory and run the command mysql -u root -p (or your username in place of root), type your PW and then run the command : SOURCE db/schema.sql; Next, you can run quit. Now you seed the database by running: npm run seed. after this executes you can run the server using npm run start. Now the server is live and you can test the routes like I did in the video in Insomnia. There is no front end of this program so insomnia is helpful. Additionally you need to creat a .env file with the private variables (this is using the dotenv package) there are three required variables: DB_NAME, that is ecommerce_db, DB_USER which is root in my case, and DB_PW which is whatever your password is. if you are confused google how to use dotenv and env files. It is just for security. The format of the variables is like this: DB_USER="root" each variable goes on its own line. Make sure the .env is in the root of whatever directory you cloned the repo into.
  ## Credits
  The started code was provided by EDX.
  ## License
  This application is covered under the MIT license, for more information please click the badge at the top of this README, which has a link to everything about the license.
  ## Tests
  Test routes in insomnia, or a similar environment!
  ## Questions
  My [Github Profile](https://github.com/itsmenickfromschool)
  Additionally you can email me at <nicholaststclairburr@gmail.com> with any questions!
