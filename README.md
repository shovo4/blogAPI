# BlogAPI

## Introduction

BlogAPI is a RESTful API built with Express.js, designed to manage blog posts. It supports operations for creating, reading, updating, and deleting blog posts. This project is structured into two main components: an API server (`index.js`) that handles the data and business logic, and a server-side rendered front-end (`server.js`) for user interactions.

## Features

- Create new blog posts
- Read existing posts, either all posts or a specific one by ID
- Update existing posts
- Delete posts
- Server-side rendered views for creating and editing posts

## Technology Stack

- Node.js
- Express.js
- Axios for HTTP requests
- EJS for server-side rendering
- Body-parser for request parsing

## Installation

Before starting, make sure you have Node.js installed on your machine.

**Clone the Repository**
```bash
git clone https://github.com/shovo4/blogAPI.git
cd blogAPI
```

- Install Dependencies
- Navigate to the project directory and run:
    - npm install
- Start the API Server
    - node index.js
- Start the Frontend Server in a New Terminal
    - node server.js

## Usage
- The API will be running at http://localhost:4000
- The frontend interface will be available at http://localhost:3000
- Navigate to http://localhost:3000 in your browser to create, view, edit, or delete posts

## API Endpoints
- GET /posts: Fetch all blog posts
- GET /posts/:id: Fetch a single post by ID
- POST /posts: Create a new post
- PATCH /posts/:id: Update an existing post
- DELETE /posts/:id: Delete a post

## Screetshots
- <img width="1459" alt="Screenshot 2024-01-08 at 12 22 12 PM" src="https://github.com/shovo4/blogAPI/assets/58551093/905d08af-6d6f-45a0-8520-b651d4325c5e">
- <img width="1208" alt="Screenshot 2024-01-08 at 12 22 23 PM" src="https://github.com/shovo4/blogAPI/assets/58551093/231b807f-ee30-4720-95e9-812e8e3c0f7e">
- <img width="1219" alt="Screenshot 2024-01-08 at 12 22 34 PM" src="https://github.com/shovo4/blogAPI/assets/58551093/419c3031-b62b-4125-a04d-78968d3a921f">



