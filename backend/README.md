<p align="center">
   <img src=".github/logo.png" width="150"/>
</p>

# Gympoint Backend


> A Rest API that helps you to manage students, enrollments, plans of a gym :rocket:

<p align="center">
  <img align="center" src="https://i.ibb.co/tM9Bynr/Web-Signin.png" alt="Web-Signin" border="0">
</p>
<br>
<p align="center">
  <img align="center" src="https://i.ibb.co/gP77Lt5/Web-Plans.png" alt="Web-Plans" border="0">
</p>
<br>

# :rocket: Features

* Students CRUD
* Plans CRUD
* Enrollments CRUD
* Students are able to create questions related to their doubts that will be sent to instructors.

It's important to mention that this is one of the applications from the **Gympoint System**


# :construction_worker: Installation

**You need to install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/) first, then in order to clone the project via HTTPS, run this command:**


# :runner: Getting Started

Run the transactions in order to configure the database schema

```npx sequelize-cli db:migrate```

Run the following command in order to start the application in a development environment:

```
 // Start the server
  yarn dev

// Run the queue responsable for the mail job
  yarn queue-dev
```

## Status Codes

Gympoint returns the following status codes in its API:

| Status Code | Description |
| :--- | :--- |
| 200 | `OK` |
| 422 | `UNPROCESSABLE ENTITY` |
| 400 | `BAD REQUEST` |
| 404 | `NOT FOUND` |
| 500 | `INTERNAL SERVER ERROR` |

# :postbox: Faq

**Question:** What are the tecnologies used in this project?

**Answer:** The tecnologies used in this project are [NodeJS](https://nodejs.org/en/) + [Express Framework](http://expressjs.com/en/) to handle the server and [Sequelize](https://sequelize.org/)



