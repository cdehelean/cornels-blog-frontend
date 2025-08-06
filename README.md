# Cornel's Blog Frontend

This is the single-page application (SPA) frontend for Cornel's Blog, built with React, React Router, and Tailwind CSS via CDN. It communicates with a backend API for blog post data.

## Features
- Modern, responsive blog UI
- Rich text editor for posts
- View, create, edit, and delete posts
- All data persisted via backend API

## Tech Stack
- React (via CDN, UMD build)
- React Router DOM v5 (via CDN)
- Tailwind CSS (via CDN)
- Babel Standalone (for JSX in-browser)

## Running Locally
1. Start the backend (see backend repo).
2. Serve this file with a static server, e.g.:
   ```
   python -m http.server 8000
   ```
3. Open [http://localhost:8000/index.html](http://localhost:8000/index.html) in your browser.

## Backend
You need to run the backend API for full functionality. See the [backend repo](../backend) for setup instructions.