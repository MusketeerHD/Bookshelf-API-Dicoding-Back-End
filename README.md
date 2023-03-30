<h1 align="center">Welcome to Bookshelf API Dicoding Back-End 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/MusketeerHD/Bookshelf-API-Dicoding-Back-End/blob/main/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/MusketeerHD/Bookshelf-API-Dicoding-Back-End/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT License" src="https://img.shields.io/badge/License-MIT License-yellow.svg" />
  </a>
  <a href="https://twitter.com/MusketeerHD" target="_blank">
    <img alt="Twitter: MusketeerHD" src="https://img.shields.io/twitter/follow/MusketeerHD.svg?style=social" />
  </a>
</p>

> This is a project submission for the &#34;Belajar Membuat Aplikasi Back-End untuk Pemula&#34; course on Dicoding which consists of building a RESTful API namely bookshelf API using the Hapi framework, Nodemon for automatic server restarting, and Postman for testing.

### 🏠 [Homepage](https://github.com/MusketeerHD/Bookshelf-API-Dicoding-Back-End)

### ✨ [Demo](https://github.com/MusketeerHD/Bookshelf-API-Dicoding-Back-End/blob/main/README.md)

## Features :

* Displays a list of books
* View book details
* Add a new book
* Change book data
* Delete books

## Prerequisites and Technology

* [Node.js](https://nodejs.org/en)
* [Hapi](https://hapi.dev/)
* [Nodemon](https://www.npmjs.com/package/nodemon)
* [Postman](https://www.postman.com/)

## Install

Clone this repo and install npm :

```sh
npm install
```

## Initialize

If you dont have or wanna change the "node_modules" use :
```sh
npm init --y
```

## Hapi & Nodemon Installation

```sh
npm install @Hapi/hapi
```
```sh
npm install nodemon
```

## Run & Usages

```sh
npm run start
```

## Access the API endpoints

Access in Bookshelf API Test Collection & Environment using Postman or any other REST client at http://localhost:9000

## API Endpoints
* `GET /books` = Get all books in the bookshelf
* `GET /books/{bookId}` = Get a book by its bookId
* `POST /books` = Add a new book to the bookshelf 
* `PUT /books/{bookId}` = Update a book by its bookId
* `DELETE /books/{bookId}` = Delete a book by its bookId

## Response Format
All API endpoints will respond with JSON data in the following format: 
```{
  "status": "success",
  "message": "Success message",
  "data": {
    // Response data
  }
}
```
If an error occurs, the response format will be:
```{
  "status": "fail",
  "message": "Error message"
}
```

## Author

👤 **Musketeer**

* Website: [MusketeerHD](https://github.com/MusketeerHD)
* Twitter: [@MusketeerHD](https://twitter.com/MusketeerHD)
* Github: [MusketeerHD](https://github.com/MusketeerHD)
* LinkedIn: [@Ahmad Azfa Dzulfaqar](https://www.linkedin.com/in/ahmad-azfa-dzulfaqar/)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2023 [Musketeer](https://github.com/Musketeer).<br />
This project is [MIT](https://github.com/MusketeerHD/Bookshelf-API-Dicoding-Back-End/blob/main/LICENSE) licensed.

***
