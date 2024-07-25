# Notes API

Notes API is a RESTful backend service that allows users to manage notes. It provides endpoints for creating, reading, updating, and deleting notes.

## Technologies Used
- Node.js
- Express.js
- Prisma ORM
- PostgreSQL

## Create a PostgreSQL Database

Create a new PostgreSQL database for the application on your local machine or a remote server.

## Add Connection String to .env File

Navigate to the notes-app-server directory and create a .env file with the following content:

`DATABASE_URL="postgresql://<username>:<password>@<host>:<port>/<dbname>?schema=public"`

Replace `<username>`, `<password>`, `<host>`, `<port>`, and `<dbname>` with your actual PostgreSQL database credentials and information.

## Run Prisma Migrations
```
npx prisma migrate dev --name init
```
## Install Dependencies
```
npm install
```
## Run server
```
npm start
```

## Postman Importe
Puede descargar el archivo de pruebas haciendo click [Aqui](recipe.postman_collection).
