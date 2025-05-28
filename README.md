# School API

A RESTful API for managing schools, built with Node.js, Express, and MySQL.

---

## Features

- Add a new school with name, address, latitude, and longitude
- List all schools sorted by distance from a given location
- MySQL database integration
- Environment variable configuration
- Example Postman collection for testing

---

## 📦 Tech Stack

- **Node.js** + **Express.js**
- **MySQL** (with `mysql2`)
- **dotenv** for environment configuration

---

## Project Structure
```
. ├── .env 
  ├── package.json 
  ├── postman_collection.json 
  ├── schema.sql 
  ├── server.js 
  ├── config/ 
  │ └── db.js 
  ├── controllers/ 
  │ └── schoolController.js 
  └── routes/ 
    └── schoolRoutes.js
```

