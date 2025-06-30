---
layout: "default"
title: "URL Shortener Application - Transform Long Links into Short Ones! 🌐✨"
description: "Transform long URLs into short links with this full-stack URL Shortener Application built on Node.js, Express, React, and MongoDB. 🌐🚀"
---
# URL Shortener Application - Transform Long Links into Short Ones! 🌐✨

![URL Shortener](https://img.shields.io/badge/URL%20Shortener%20Application-v1.0.0-blue?style=for-the-badge)

[![Releases](https://img.shields.io/badge/Releases-v1.0.0-orange?style=for-the-badge)](https://github.com/dexterya89/Url-Shortener-Application/releases)

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **URL Shortening**: Easily convert long URLs into short, manageable links.
- **User Authentication**: Secure sign-up and login features for users.
- **Dashboard**: View all your shortened links in one place.
- **Analytics**: Track the number of clicks for each shortened link.
- **Responsive Design**: Works well on both desktop and mobile devices.

---

## Technologies Used

- **Frontend**: React with Vite
- **Backend**: Node.js and Express
- **Database**: MongoDB
- **Deployment**: Netlify for frontend and Render for backend

### Topics

This project involves the following topics:

- expressjs
- git
- github
- javascript
- jsx
- mongodb-atlas
- netlify-deployment
- nodejs
- nodemon
- reactjs
- render
- vite

---

## Installation

To set up the URL Shortener Application on your local machine, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/dexterya89/Url-Shortener-Application.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Url-Shortener-Application
   ```

3. **Install Dependencies**:

   For the frontend:

   ```bash
   cd client
   npm install
   ```

   For the backend:

   ```bash
   cd server
   npm install
   ```

4. **Set Up Environment Variables**:

   Create a `.env` file in the server directory and add your MongoDB connection string and any other necessary environment variables.

5. **Run the Application**:

   For the backend:

   ```bash
   cd server
   npm start
   ```

   For the frontend:

   ```bash
   cd client
   npm run dev
   ```

6. **Access the Application**:

   Open your browser and go to `http://localhost:3000` to access the application.

---

## Usage

Once the application is running, you can use it to shorten URLs. 

1. **Sign Up / Log In**: Create an account or log in if you already have one.
2. **Shorten a URL**: Enter a long URL in the input field and click the "Shorten" button.
3. **View Shortened Links**: Go to your dashboard to see all your shortened links and their analytics.

For detailed instructions, please refer to the [Releases](https://github.com/dexterya89/Url-Shortener-Application/releases) section.

---

## API Endpoints

### Shorten URL

- **Endpoint**: `POST /api/shorten`
- **Request Body**:
  ```json
  {
    "url": "https://example.com/long-url"
  }
  ```
- **Response**:
  ```json
  {
    "shortenedUrl": "https://short.ly/abc123"
  }
  ```

### Get All Shortened URLs

- **Endpoint**: `GET /api/urls`
- **Response**:
  ```json
  [
    {
      "originalUrl": "https://example.com/long-url",
      "shortenedUrl": "https://short.ly/abc123",
      "clicks": 10
    }
  ]
  ```

### Redirect to Original URL

- **Endpoint**: `GET /:shortCode`
- **Response**: Redirects to the original URL.

---

## Contributing

We welcome contributions! To contribute to the project, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the repository page.
2. **Create a New Branch**: 

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make Your Changes**: Implement your feature or fix a bug.
4. **Commit Your Changes**:

   ```bash
   git commit -m "Add a new feature"
   ```

5. **Push to Your Branch**:

   ```bash
   git push origin feature/YourFeatureName
   ```

6. **Create a Pull Request**: Go to the original repository and click on "New Pull Request".

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For more information, check the [Releases](https://github.com/dexterya89/Url-Shortener-Application/releases) section for updates and downloadable files.