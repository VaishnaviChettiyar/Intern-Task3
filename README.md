# Intern-Task3
Book Management REST API

This project is a simple RESTful API built using Node.js and Express to manage a collection of books. The main goal is to demonstrate how to perform basic CRUD (Create, Read, Update, Delete) operations without using a database. All data is stored temporarily in memory.

Objective

To build a REST API that allows users to:
- View all books
- Add a new book
- Update existing book details
- Delete a book

The project uses only in-memory data storage(no database), meaning all book records exist only while the server is running. Once the server stops, the data is lost.

Technologies Used

- Node.js: A JavaScript runtime used for building fast and scalable network applications.
- Express.js: A minimal and flexible Node.js web application framework for handling routes and middleware.
- Postman: A tool used for testing and interacting with the API endpoints during development.

#Steps to Create the Project

- Create a project folder : 
Create a new folder for your project (e.g., book-api).

- Initialize the project : 
Open Command Prompt or terminal inside the folder and run npm init -y to create a package.json file.

- Install Express : 
Run npm install express to install the Express framework.

- Create the main server file : 
In VS Code, create a file named server.js.

- Set up a basic Express server : 
Write code in server.js to start a server on port 3000.

- Create an in-memory array : 
Define an array to store book objects in the format: { id, title, author }.

- Implement API endpoints : 

GET /books – Returns all books.
POST /books – Adds a new book.
PUT /books/:id – Updates a book by its ID.
DELETE /books/:id – Deletes a book by its ID.

- Run the server : 
Use node server.js in the terminal to start the server.

- Test with Postman : 
Use Postman to test all the API endpoints.

This REST API serves as a foundational project for understanding back-end development using Node.js and Express. It demonstrates how to structure an API, manage data in memory, and perform standard operations needed in most web applications.
