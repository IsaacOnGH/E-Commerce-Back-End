# E-Commerce-Back-End

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

E-Commerce Back End is a backend application for an e-commerce website, built using Express.js and Sequelize. It provides a suite of services for managing categories, products, and tags within the e-commerce platform. The application uses a MySQL database to store and retrieve data.

## Features

- Connect to a MySQL database using Sequelize.
- Create and populate a development database with test data using migrations and seeders.
- Define and handle API routes for CRUD operations on categories, products, and tags.
- Synchronize Sequelize models with the MySQL database on server startup.

## Installation

To set up and use the E-Commerce Back End application, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory using your terminal.
3. Install the necessary dependencies by running the command: `npm install`

## Database Configuration

The application uses Sequelize to interact with a MySQL database. To configure the database, create a `.env` file in the project root directory and add your database credentials:


## Dependencies

The following npm packages are used in this project:

- [express](https://www.npmjs.com/package/express): Web framework for Node.js.
- [sequelize](https://www.npmjs.com/package/sequelize): Promise-based Node.js ORM for MySQL.
- [mysql2](https://www.npmjs.com/package/mysql2): MySQL client for Node.js.

You can install them using the command: `npm install express sequelize mysql2`

## Running the Server

1. Open your terminal.
2. Navigate to the project directory.
3. Run the application using the command: `npm start`
4. The server will start, and Sequelize models will be synced with the MySQL database.

## API Routes

- `GET /api/categories`: Get all categories.
- `GET /api/products`: Get all products.
- `GET /api/tags`: Get all tags.

- `POST /api/categories`: Create a new category.
- `POST /api/products`: Create a new product.
- `POST /api/tags`: Create a new tag.

- `PUT /api/categories/:id`: Update a category.
- `PUT /api/products/:id`: Update a product.
- `PUT /api/tags/:id`: Update a tag.

- `DELETE /api/categories/:id`: Delete a category.
- `DELETE /api/products/:id`: Delete a product.
- `DELETE /api/tags/:id`: Delete a tag.

## Testing

Use a tool like Insomnia Core or Postman to test the API routes. Test both the GET and CRUD operations to ensure the functionality is working as expected.

## Video Walkthrough

For a detailed demonstration of the application's functionality and how to run it, please refer to the [Video Walkthrough](https://drive.google.com/file/d/1VQKoBmSqYtxgfh96kIdoU4EOaJ1sucVY/view) provided.

## Contributing

Contributions are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.

## License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Questions

If you have questions or need further assistance, feel free to reach out:
- GitHub: [IsaacOnGH](https://github.com/IsaacOnGH)
- Email: isaac.melanson@yahoo.com
