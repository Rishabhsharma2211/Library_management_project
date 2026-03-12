# Library Management Backend

This is a backend API for a Library Management System built using Node.js, Express, and MongoDB.

## Features
- Add a new book
- Get all books
- Search books by title
- Update book details
- Delete books

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- Nodemon

## Project Structure
config/
controllers/
models/
routes/
server.js

## Installation

Clone the repository:

git clone https://github.com/Rishabhsharma2211/Library_management_project.git

Install dependencies:

npm install

Run the server:

npm run dev

Server runs on:
http://localhost:5000

## API Endpoints

GET /books  
POST /books  
PUT /books/:id  
DELETE /books/:id  
GET /books/search?title=bookname
