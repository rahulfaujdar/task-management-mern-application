## Task Manager with User Authentication

Live Demo : https://rahulfaujdar.github.io/task-management-mern-application/
### Project Setup

```bash
node version - v16.20.1

# install project
$ git clone https://github.com/rahulfaujdar/task-management-mern-application.git
# open app directory
$ cd task-management-mern-application


# setup and install dependencies for frontend
$ cd frontend && npm install
# frontend start
$ npm start


# setup and install dependencies for backend
$ cd backend && yarn install
# set database credentials
# make .env file
# paste code .env.example file to .env file
# provide database credentials in .env file
# run database migrations (Table)
$ npx sequelize-cli db:migrate 
# backend start
$ npm start
```