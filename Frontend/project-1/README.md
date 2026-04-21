# Cloud Image Upload App (Frontend)

This is the frontend of a Cloud Image Upload Application built using React.js.
It allows users to upload images from their local device with a caption and view all uploaded posts in a feed.

---

## Features

* Upload image from local device using file input
* Add caption with image
* Send data to backend using FormData
* Redirect to feed after successful upload
* Fetch and display all posts from backend
* Show image with caption in feed
* Handle empty state when no posts are available

---

## Tech Stack

* React.js
* Axios
* Tailwind CSS

---

## Functionality Overview

### Create Post

* User selects an image file
* Adds a caption
* On submit:

  * Form data is sent to backend API (`/create_post`)
  * After successful upload, user is redirected to `/feed`

### Feed Page

* Fetches all posts from backend API (`/posts`)
* Displays:

  * Uploaded image
  * Caption
* If no posts are available, shows a message

---

## API Endpoints Used

* POST `/create_post` → Upload image and caption
* GET `/posts` → Fetch all posts

---

## Author

Siddhi Sisodiya
