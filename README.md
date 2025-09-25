# Books API

This is a simple REST API to manage a list of books using Node.js and Express.  
All data is stored in memory (no database required).

---

## Project Setup

1. Clone the repository:  
   ```bash
   git clone <your-repo-url>
Navigate to the project folder:

Copy code
cd books-api
Install dependencies:

Copy code
npm install
Start the server:

Copy code
node server.js
The server runs at:

arduino
Copy code
http://localhost:3000

# Books API - Endpoints

## GET /books
- Returns all books.
- Method: GET
- URL: http://localhost:3000/books

## POST /books
- Adds a new book.
- Method: POST
- URL: http://localhost:3000/books
- Request Body (JSON):
```json
{
  "title": "Book Title",
  "author": "Author Name"
}
PUT /books/:id
Updates an existing book by ID.

Method: PUT

URL: http://localhost:3000/books/:id

Request Body (JSON):

json
Copy code
{
  "title": "Updated Title",
  "author": "Updated Author"
}
DELETE /books/:id
Deletes a book by ID.

Method: DELETE

URL: http://localhost:3000/books/:id
