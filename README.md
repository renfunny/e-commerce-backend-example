# E-commerce Backend Using Sequelize

## License

[![Project license](https://img.shields.io/badge/license-Apache2.0-green))](https://opensource.org/licenses/Apache-2.0)

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [Testing](#testing)
- [Contact Information](#contact-information)

## Description

This project required creating the backend of a simple e-commerce store database with 4 tables/models: category, product, product tag, and tags. This was done using an ORM called sequelize to create all these tables and their respective columns and rules, as well as associating each table/model to create relationships between them, and lastly, create the routes to perform RESTful CRUD operations such as create, read, update, and delete data from each table/model. This project was a great way to get confortable and familiarize myself with an ORM such as sequelize instead of using MySQL queries. It was a great way to learn the capabilities and advantages of using an ORM when creating a backend, and it also helped me visualize how an e-commerce backend might look like.

## Installation

This app requires Node.js.
Once Node.js is installed all dependencies must be installed by running:

```
npm install

```

Then the database must be created using MySQL shell commands, which are located in the `schema.sql` file inside the `db` folder. Thn we can go ahead and seed our database by running:

```
 npm run seed

```

Lastly we have to initiate the server by running:

```
 node ./server.js

```

## Usage

This project provides a great foundation of the capabilities of sequelize, which can be used in the future when working on other projects. It helps by providing a guideline on how to properly use sequelize and how to set everything up.
For a video walkthrough as to how the application works and how it can be used please click the following link: [https://drive.google.com/file/d/1kxIOZ7F7DFVxl5yBtzI0JzAce2xOgluv/view](https://drive.google.com/file/d/1kxIOZ7F7DFVxl5yBtzI0JzAce2xOgluv/view)

## License

Apache2.0

## Contribution

The project is done, but any feedback on how this can be improved would be much appreciated!

## Testing

There is no tests in this project but the user can check for the functionality of the project by using an application like Insomnia or Postman to check that the routes and the CRUD operations work.

## Contact Information

- GitHub: [renfunny](https://github.com/renfunny)
- Email: [ren99cordova@gmail.com](mailto:ren99cordova@gmail.com)
