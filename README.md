# Introduction

### This is a Shared Lists App with local Authentication.

### Live site https://sharedtodos.bobbynoodles.com

Users can create accounts, or sign in on the initial / home page.
Once logged to their account they're redirected to the lists page.

From the list page, users can:

- create and delete named lists,
- share those lists with other users,
- and access the currently available list on their profile.

Each individual list, has tasks and autorized users can perform CRUD operations:

- create a task
- read/show the tasks
- mark complete (update)
- delete the task

<h2>This app uses MVC architecture </h2>

---

# Packages/Dependencies used

bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

---

# To run this project on a code editor:

1. Install all the dependencies or node packages used for development via Terminal

`npm install`

2. Create a `.env` file and add the following as `key: value`

- PORT: 2121 (can be any port example: 3000)
- DB_STRING: `your database URI`

---

Have fun testing and improving it! 😎
