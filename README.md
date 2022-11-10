# StoreBackEnd

## Purpose
An application for the back end of an ecommerce store. See link for an example https://drive.google.com/file/d/1sXiO0_ZYVkcO4GilzJGpxL6JT3Mbyr7n/view?usp=share_link. 

## Installation

After cloning the repository run `npm install` to install all the needed packages from the package.json file. Then, make a `.env` file with the database name, database user, and database password.


## Built With
* Express.js
* Sequelize
* MySQL2
* Dotenv


## Usage
You will have to log into mysql and create a database and then run `source db/schema.sql;`. After that run `quit;`. Then, run `npm run seed` and finally run `npm start`. From there you can use Insomnia to test the routes. 

## Contribution
Made by Cy Howard
