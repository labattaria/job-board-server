# Job Board server

---

[![GraphQL](https://img.shields.io/badge/GraphQl-E10098?style=for-the-badge&logo=graphql&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
[![ApolloGraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)](#)
[![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)](#)
[![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)](#)
[![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)](#)

This is the Express/GraphQL/Apollo server, designed and configured for the **Job Board Application**
This server is only part of the application, the second part (the client) is located here:
The app in this repo is deployed at [https://render.com](https://render.com), hosting public URL: [https://job-board-server-mq1m.onrender.com](https://job-board-server-mq1m.onrender.com)
But you can use this server manually on your local machine

## Used dependencies:

- **GraphQL** - Core GraphQL library
- **apollo-server** - GraphQL server that works with any GraphQL schema
- **SQLite** - A lightweight, self-contained SQL database engine. It stores the entire database in a single file
- **JWT (JSON Web Token)** - A compact, URL-safe token format used for securely transmitting information between parties. Commonly used for authentication and authorization in web applications
- **Nodemon** - A development utility that automatically restarts your Node.js server when it detects file changes

The full list of dependencies can be found in the package.json file.

## Contents

- [Installation](#installation)
- [Usage](#usage)

### Installation

1. Clone the repository:

```shell
git clone https://github.com/labattaria/job-board-server.git
```

2. Install project dependencies:

```shell
cd job-board-server
npm install
```

### Usage

Start the server using the following command:

```shell
npm start
```

Server will be located at **http://localhost:9000/**
