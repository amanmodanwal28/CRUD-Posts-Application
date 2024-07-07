# CRUD Posts Application

## Overview

This project is a simple CRUD (Create, Read, Update, Delete) application built using Node.js and Express.js. It allows users to create, view, edit, and delete posts. This application demonstrates basic CRUD operations, middleware usage, and view rendering with EJS.

## Features

- **Create Post**: Users can create new posts with a unique ID, username, and content.
- **Read Posts**: Users can view a list of all posts or a specific post by ID.
- **Update Post**: Users can edit the content of an existing post.
- **Delete Post**: Users can delete a post by ID.

## Project Structure

- **server.js**: The main entry point of the application.
- **views/**: Contains EJS templates for rendering pages.
  - `index.ejs`: Renders the list of posts.
  - `new.ejs`: Renders the form to create a new post.
  - `show.ejs`: Renders a specific post.
  - `edit.ejs`: Renders the form to edit a post.
- **public/**: Contains static files (CSS, JavaScript, images, etc.).

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- npm (Node Package Manager) installed.

### Installation

1. Clone the repository:
   ```bash
   https://github.com/amanmodanwal28/CRUD-Posts-Application.git

2. Navigate to the project directory:
    ```bash
    cd CRUD-Posts-Application

3. Install dependencies:
   ```bash
    npm install

### Installation

1. Start the server:
    ```bash
    node index.js

2. Open your web browser and go to:
   ```bash
    http://localhost:3000/posts


# Usage

## Creating a Post

1. Navigate to `/posts/new`.
2. Fill in the form with a username and content.
3. Click "Create Post" to add the post.

## Viewing Posts

1. Navigate to `/posts` to see all posts.
2. Click on a post's title to view its details.

## Editing a Post

1. Navigate to `/posts/:id/edit` (replace `:id` with the actual post ID).
2. Update the content and submit the form.

## Deleting a Post

1. Navigate to `/posts`.
2. Click the "Delete" button next to the post you want to delete.

## Technologies Used

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **EJS**: Embedded JavaScript templating.
- **UUID**: Library to generate unique IDs.
- **Method-Override**: Middleware to use HTTP verbs such as PUT or DELETE in places where the client doesn't support it.


## License

This project is licensed under the MIT License.
