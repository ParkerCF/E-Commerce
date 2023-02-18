
# E-Commerce Back End application

This is a back end application for an e-commerce site. This application uses Express.js API and Sequilize to interact with a MySQL database. 

## Usage

The user will run "node index.js". The user can then open up the localhost in Insomnia. By navigating to the api/ folder the user can then navigate to either tags, products, or categories. The user is given a functional Express.ks API. When the user adds their database name, MYSQL username, and MYSQL passowrd to a .env file, the user is then able to connect to a database using Sequelize. When the user enters the schema and seed commands then a development database is created and is seeded witht he test data. After running "node index.js" the server is strarted and the Sequelize moedls are synced to the MySQL database. When the user opens API get routes in Insomnia for categories, products, or tags thent he data for each of these routes is displated in a formatted JSON. When the user tests API POST, PUT, and DELETE routes in Insomnia then they are able to successfully create, update, and delete data in their database. 

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Demo

Insert gif or link to demo


## Features

- Uses JavaScript
- Uses Node.js
- Uses Sequelize
- Uses Express.js API 
- Uses MySQL


## License

[MIT](https://choosealicense.com/licenses/mit/)

