# ECommerceBackEnd

# EmployeeTracker

### GitHub Repo: https://github.com/kellys-tech/ECommerceBackEnd
### Video: https://youtu.be/ALrR7BDN12o

![License](https://img.shields.io/badge/license-MIT-blue)

*This is an E-Commerce back end express application. The app is designed to interact with a MySQL database through sequelize.*

## Employee Tracker created using:
* Sequelize
* MySql2
* Express
* DotEnv

## Features
### Create a database and seed data
* User can create a database in my MySqlWorkbench using the code in the schema file
* User will run `npm start` from the terminal to connect to the database and create the tables
* User will seed the database using the command `npm run seed` send data to the database
### Create/Post new data using an API client (like Postman)
* User can create new Categories
* User can create new Products
* User can create new Tags
### Read/Get the table data using an API client (like Postman)
* User can read all the data in the Category table
* User can read one category's data in the Cateogry table
* User can read all the data in the Product table
* User can read one product's data in the Product table
* User can read all the data in the Tag table
* User can read one tag's data in the tag table
### Update the table data using an API client (like Postman)
* User can update a category in the Category table
* User can update a product in the Product table
* User can update a tag in the tag table
### Delete data from a table using an API client (like Postman)
* User can delete a category from the Category table
* User can delete a product from the Prouct table
* User can delete a tag from the tag table
    
# How to use
* Fork the repo using the link above
* Run command `npm i` to install dependencies from the package.json file
* There is example environment information in the .env-Example file. The user will need ot create their own .env file using their MySQLWorkbench user name and password. 
* Run command 'npm start' to connect to the database and create the tables
* Install an API client like Postman to run the GET, PUT, POST and DELETE routes.
* Use the video linked above for a demonstration

## License
This project is licensed under the terms of the MIT license.

## Contributing
If you would like to contribute please contact me directly by submitting an issue through my github repo.

## Contact
If you have any questions you can contact me through my github repo, listed at the top of the page or by emailing me at kellysmith.r77@gmail.com