# My-Book-Search-Engine 📚

![License Badge](https://img.shields.io/github/license/jak3ster/my-book-search-engine) ![Top Language](https://img.shields.io/github/languages/top/jak3ster/my-book-search-engine)

  ---
Refactored a fully functioning Google Books API search engine built with a RESTful API to be a GraphQL API built with Apollo Server.

This app is built using the MERN stack with a React front end, [CloudMongoDB](https://cloud.mongodb.com/), and [NodeJS](https://nodejs.org/en/)/[Express](https://expressjs.com/) server, API and set up to allow users to save book searches to the back end.

## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Acceptance Criteria

```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
```

## Installation 🔨

1. Download or clone repository
2. Node.js is required to run the application
3. `npm install` to install the required npm packages

## Usage 📎

* The application is invoked by running `npm start` in the command line  
* Open a browser and navigate to <http://localhost:3000/>
* Shows the homepage to interact with the portfolio site.

## Demo 📷

*Main Page:* 🌎

![Main Page](/client/src/assets/images/main.png)

*Login Page:* 🚪

![Login Page](/client/src/assets/images/login.png)

*Search Results:* 🔍

![Search Results](/client/src/assets/images/search.png)

*Saved Books:* 💾

![Saved Books](/client/src/assets/images/saved.png)

## Links 🔗

* [Heroku](https://jak3ster-booksearchengine.herokuapp.com/)
* [Github](https://github.com/jak3ster/my-book-search-engine/)

## Features 🧩

* [NodeJS](https://nodejs.org/en/)
* [Express](https://expressjs.com/)
* bcrypt
* jsonwebtoken
* jwt-decode
* mongoose
* nodemon
* bootstrap
* [APOLLO](https://www.apollographql.com/)
  * apollo-server-express
  * apollo/react-hooks
  * apollo-boost
* [GraphQL](https://graphql.org/)
  * graphql-tag
* [React](https://reactjs.org/)
  * react-bootstrap
  * react-dom
  * react-router-dom
  * react-scripts

## Contact

🔗 Links in Bio @[jak3ster](https://github.com/jak3ster)

![Email Badge](https://img.shields.io/badge/Email%20Me-mailto:jak3ster%40hotmail.com-d8bfd8)

---
This project is MIT licensed. &copy; 2022
