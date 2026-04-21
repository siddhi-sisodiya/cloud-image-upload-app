# Cloud Image Upload App

Cloud Image Upload App is a full-stack web application that allows users to upload images, store them on a cloud service, and view them in a feed.

---

## Features

* Upload images from local device
* Store images on cloud using ImageKit
* Save image URLs and captions in MongoDB database
* Fetch and display images in a feed
* REST API integration (GET & POST requests)
* Responsive UI using Tailwind CSS

---

## Tech Stack

* React.js (Frontend)
* Tailwind CSS
* JavaScript (ES6)
* Node.js (Backend)
* Express.js
* MongoDB (Database)
* ImageKit (Cloud Storage)

---

## Project Structure

project/
├── frontend/   → React application (UI)
├── backend/    → Node.js + Express API
└── README.md

---

## Frontend (React)

* Built using React.js
* Provides user interface for image upload
* Uses file input to select images from local system
* Sends image and caption to backend using FormData
* Fetches and displays posts in feed using API

---

## Backend (Node.js & Express)

* Handles API requests from frontend
* Uploads images to ImageKit cloud service
* Generates image URL after upload
* Stores image URL and caption in MongoDB
* Provides API endpoints for:

  * Uploading images (POST)
  * Fetching all posts (GET)

---

## Database (MongoDB)

* MongoDB is used to store image data
* Each post contains:

  * Image URL
  * Caption
* Backend connects to MongoDB using a database connection
* Data is stored in collections and retrieved when needed

---

## API Endpoints

* POST `/create_post` → Upload image and caption
* GET `/posts` → Fetch all posts

---

## How It Works

* User selects image from frontend
* Image is sent to backend
* Backend uploads image to ImageKit
* Image URL is generated
* URL and caption are stored in MongoDB
* Frontend fetches and displays images

---

## Learning Outcomes

* Full-stack development understanding
* React frontend development
* REST API creation using Node.js & Express
* Database handling with MongoDB
* Cloud storage integration
* File upload handling

---

## Repository

https://github.com/siddhi-sisodiya/cloud-image-upload-app

---

## Author

Siddhi Sisodiya
