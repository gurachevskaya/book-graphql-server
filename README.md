# GraphQL Server with Apollo

This GraphQL server, developed using Apollo, is specifically designed for learning purposes and provides a simple and efficient way to manage books. With this server, you can perform various operations such as fetching existing books, adding new books, and removing existing books.
The main goal is to understand the fundamentals of GraphQL implementation with Apollo.

The server is built on the Apollo framework, which is a popular choice for creating GraphQL servers due to its excellent tooling and developer-friendly features. 

## Retrieve books or exact book

To retrieve books, you can send a GraphQL query **books** specifying the desired fields. The server will respond with the requested information, enabling you to easily display book details, such as title and author.\

To retrieve a book, you can send a GraphQL query **book** with a required id.

## Adding a new book

Adding a new book is straightforward. You can send a mutation request **addBook** with the necessary information, including the book's attributes like title, author. The server will process the request, create a new book entry, and return the added book to indicate the operation's completion.

## Removing a new book

Similarly, removing a book involves sending a mutation request **removeBook** with the book's unique identifier. The server will identify the book based on the provided identifier, remove it from the database, and return the deleted book.


## Starting a server locally
- node app.js / nodemon app.js
