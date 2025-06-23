# 🌍 WanderLust

WanderLust is a full-stack travel management platform designed to help users explore, share, and manage travel experiences. It includes features like location mapping, image uploads, and secure authentication — all built with the MERN stack.

## 🔧 Tech Stack

- **Frontend:** Bootstrap, HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js (MVC architecture)
- **Database:** MongoDB Atlas
- **APIs & Services:** Mapbox (geolocation), Cloudinary (image upload)

## ✨ Features

- Responsive UI for exploring destinations
- User authentication and authorization
- Create, Read, Update, Delete (CRUD) for travel entries
- Map integration with Mapbox
- Image storage via Cloudinary

## 📁 Project Structure

WanderLust/

├── controllers/ # Logic for route handling

├── models/ # Mongoose schemas

├── public/ # Static assets (CSS, JS, images)

├── routes/ # Express route files

├── utils/ # Utility functions

├── views/ # EJS templates

├── middleware.js # Custom middleware

├── cloudConfig.js # Cloudinary configuration

├── schema.js # Input validation schemas

├── app.js # Main app entry point

├── package.json # Project metadata and dependencies

## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB Atlas account
- Mapbox token
- Cloudinary account

### Installation


#### Clone the repository

```
git clone https://github.com/Madhumita211/WanderLust.git
cd WanderLust
```

#### Install server dependencies

```
npm install
```

#### Set environment variables
#### (MongoDB URI, Cloudinary keys, Mapbox token, etc.)
##### Create a .env file and add the following:

```
MONGO_URI=your_mongodb_connection_string
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MAPBOX_TOKEN=your_mapbox_token
SESSION_SECRET=your_session_secret
```

#### Run the application

```
npm start
```
---

## 💻 Usage

- Navigate to http://localhost:3000
- Sign up and log in to manage travel posts
- Upload places with images and map coordinates
- Edit or delete your own travel entries


## 📸 Screenshots

### 🏠 Home Page

![WanderLust Home Page](https://github.com/user-attachments/assets/cb88fdb4-8604-4f01-97d6-8029979efbdf)

### 📍 Destination with Map

![WanderLust Listing Page](https://github.com/user-attachments/assets/b78fea30-9a3d-4a4c-80aa-017f0a81516c)

## 📬 Contact

Madhumita Das

📧 madhumita021199@gmail.com

🔗 GitHub: https://github.com/Madhumita211

🔗 LinkedIn: https://www.linkedin.com/in/madhumita-das211/

## 📄 License

This project is licensed under the [MIT License](LICENSE).
