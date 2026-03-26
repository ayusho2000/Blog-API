#  Blog API

The **Blog API** is a RESTful backend application built using Node.js and Express that allows users to manage blog posts through standard CRUD operations.

It uses an in-memory data store, making it lightweight and ideal for learning backend development concepts.

---

##  Features

###  Post Management
- Get all blog posts  
- Get a single post by ID  
- Create new posts  
- Update existing posts  
- Delete posts  

###  API Functionality
- RESTful API design  
- Fast and lightweight  
- Handles JSON requests  

---

##  Tech Stack

### Backend
- Node.js  
- Express.js  

### Middleware
- body-parser  

---

##  System Workflow

1. User sends API request  
2. Server processes request  
3. Data is retrieved or modified  
4. Response is returned in JSON format  

---

##  API Endpoints

| Method | Endpoint        | Description          |
|--------|----------------|----------------------|
| GET    | /posts         | Get all posts        |
| GET    | /posts/:id     | Get single post      |
| POST   | /posts         | Create post          |
| PATCH  | /posts/:id     | Update post          |
| DELETE | /posts/:id     | Delete post          |

---

##  Purpose of the Project

This project aims to:

- Understand REST API development  
- Implement CRUD operations  
- Learn Express routing and middleware  
- Build backend foundations  

---

## ⚠️ Note

- Data is stored in-memory  
- All data resets when the server restarts  
- Not intended for production use  

---

##  Future Improvements

- Integrate database (MongoDB/PostgreSQL)  
- Add authentication and authorization  
- Implement validation and error handling  
- Add pagination and filtering  

---

