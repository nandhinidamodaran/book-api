# Book Management REST API – Task 3

# Description
A simple REST API built with Node.js and Express.js to manage a list of books.  
This API performs basic CRUD operations:

-  GET /books – Get all books
-  POST `/books – Add a new book
-  PUT /books/:id – Update a book by ID
- DELETE /books/:id – Delete a book by ID

All data is stored in memory, so changes reset on server restart.

---

# Technologies Used

- Node.js
- Express.js
- Postman (for testing)

---

##  How to Run This Project

1. Clone the Repository
   git clone https://github.com/nandhinidamodaran/book-api.git
   cd book-api
Install Dependencies

bash
Copy
Edit
npm install
Start the Server

bash
Copy
Edit
node index.js
Server will run at:

arduino
Copy
Edit
http://localhost:3000
 API Endpoints
 GET /books:-
Returns all books

Response:

json
Copy
Edit
[]
POST /books:-
Adds a new book

Request Body:

json
Copy
Edit
{
  "title": "Atomic Habits",
  "author": "James Clear"
}
Response:

json
Copy
Edit
{
  "id": 1,
  "title": "Atomic Habits",
  "author": "James Clear"
}
 PUT /books/:id:-
Updates book by ID

Request Body:

json
Copy
Edit
{
  "title": "Updated Title",
  "author": "Updated Author"
}
➤ DELETE /books/:id
Deletes book by ID

Response:

Status: 204 No Content

 Postman Testing
Use Postman to send requests to:

Copy
Edit
http://localhost:3000/books
Try all 4 operations: GET, POST, PUT, DELETE.

 Author
Nandhini Damodaran
 username :https://github.com/nandhinidamodaran/book-api.git
