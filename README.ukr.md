**Read in another language: [Українська](README.ukr.md), [English](README.md).**

# Job Board server

---

[![GraphQL](https://img.shields.io/badge/GraphQl-E10098?style=for-the-badge&logo=graphql&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
[![ApolloGraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)](#)
[![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)](#)
[![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)](#)
[![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)](#)

Це сервер Express/GraphQL/Apollo, створений та налаштований для додатку Job Board

Цей сервер — лише частина додатку, друга частина (клієнтська) знаходиться в цьому репо: [Job Board Client](https://github.com/labattaria/job-board-client)

Застосунок у цьому репозиторії розгорнуто за адресою: [https://render.com](https://render.com), за цією URL-адресою: [https://job-board-server-mq1m.onrender.com](https://job-board-server-mq1m.onrender.com)

Але ви можете використовувати цей сервер вручну на своєму локальному комп’ютері.

## Used dependencies:

- **GraphQL** - Основна бібліотека GraphQL
- **Apollo-server** - GraphQL-сервер, який працює з будь-якою схемою GraphQL
- **SQLite** - Легка, автономна SQL-база даних. Весь вміст зберігається в одному файлі
- **JWT (JSON Web Token)** - Компактний, безпечний для URL формат токена, який використовується для безпечної передачі інформації між сторонами. Зазвичай застосовується для автентифікації та авторизації у вебзастосунках
- **Nodemon** - Утиліта для розробки, яка автоматично перезапускає ваш сервер Node.js при виявленні змін у файлах

Повний список залежностей можна знайти у файлі package.json.

---

## Вміст

- [Встановлення](#Встановлення)
- [Використання](#Використання)

### Встановлення

1. Склонуйте репозиторій:

```shell
git clone https://github.com/labattaria/job-board-server.git
```

2. Встановіть залежності проекту:

```shell
cd job-board-server
npm install
```

### Використання

Запустіть сервер за допомогою наступної команди:

```shell
npm start
```

Сервер буде доступний за адресою **http://localhost:9000/**
