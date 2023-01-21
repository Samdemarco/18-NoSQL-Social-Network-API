# NoSQL: Social Network API

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This is project is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. 

The application uses: `Node.js`, `MongoDB & Mongoose`, `Express.js`, and utilizes ODM (Object Data Modeling) framework.

Here is a snapshot of API calls using Insomnia:
    <br />
![Tech Blog](TechBlogSnapshot.png)


## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [License](#license)
- [Tests](#tests)

## Installation

To run your own version of the app do the following:
1. Clone this git repo to your computer
2. In your terminal type `npm install` 
3. Once all dependencies are installed type `npm run start` or `npm run dev` for automatic "server restart" when modifying code 
4. Use Insomnia to execute various CRUD/API calls


## Credits

* Samdemarco

## License

MIT License

## Tests

N/A
