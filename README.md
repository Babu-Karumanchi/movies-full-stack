
# 🎬 Movies Full Stack

A comprehensive full-stack movie application that enables users to browse, review, and manage their favorite films. Built with modern web technologies to provide an interactive and seamless experience.

---

## 📑 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

---

## 📌 About

**Movies Full Stack** is a dynamic web app that allows users to:

- Explore a large collection of movies.
- View detailed movie information including reviews and trailers.
- Create and manage a personalized watchlist.
- Read and submit movie reviews.

This project demonstrates the integration of a **React.js** frontend with a **Java Spring Boot** backend and **MongoDB** database.

---

## 🚀 Features

- 🔍 **Movie Browsing** – Search and filter movies by title, genre, or rating.
- 🎥 **Detailed Movie Pages** – View trailers, cast info, ratings, and user reviews.
- 📄 **Watchlist Management** – Add and remove movies from your favorites.
- 📝 **Movie Reviews** – Add and view reviews for each movie.
- 📱 **Responsive Design** – Optimized for both desktop and mobile.

> 🔐 *User authentication will be added in a future version.*

---

## 🧰 Tech Stack

- **Frontend**: React.js, Bootstrap, CSS
- **Backend**: Java Spring Boot
- **Database**: MongoDB
- **Version Control**: Git & GitHub
- **API Testing**: Postman

---

## 📁 Project Structure

```

movies-full-stack/
├── backend/          # Spring Boot backend
│   └── src/
├── frontend/         # React.js frontend
│   └── src/
└── README.md

````

---

## 🛠️ Installation

### Prerequisites

Ensure the following are installed:

- Java JDK 17
- Maven
- Node.js & npm
- MongoDB
- Git

---

### 1. Clone the Repository

```bash
git clone https://github.com/Babu-Karumanchi/movies-full-stack.git
cd movies-full-stack
````

---

### 2. Set Environment Variables

#### Backend (`backend/.env`)

Create a `.env` file inside the `backend` folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

#### Frontend (`frontend/.env`)

Create a `.env` file inside the `frontend` folder:

```
REACT_APP_API_URL=http://localhost:5000/api
```

---

### 3. Install Dependencies

#### Backend (Spring Boot)

```bash
cd backend
./mvnw clean install
```

#### Frontend (React)

```bash
cd ../frontend
npm install
```

---

## ▶️ Usage

### 1. Start MongoDB

Ensure MongoDB is running on your system.

### 2. Run Backend

```bash
cd backend
./mvnw spring-boot:run
```

### 3. Run Frontend

```bash
cd frontend
npm start
```

Access the app at: [http://localhost:3000](http://localhost:3000)

---

## 📡 API Endpoints

### 🔹 Movies

* `GET /api/movies` – Get all movies
* `GET /api/movies/:id` – Get a movie by ID
* `POST /api/movies` – Add a new movie
* `PUT /api/movies/:id` – Update a movie
* `DELETE /api/movies/:id` – Delete a movie

### 🔹 Reviews

* `POST /api/reviews` – Add a review
* `GET /api/reviews/:movieId` – Get reviews for a movie

> 🧩 *Endpoints related to user registration, login, and protected routes will be added in a future update.*

---


## 👥 Authors

* **Frontend**: Developed by **Yash Kunjir**
* **Backend**: Developed by **Babu Karumanchi**

---


## 🌐 Links

* **GitHub Repo**: [https://github.com/Babu-Karumanchi/movies-full-stack](https://github.com/Babu-Karumanchi/movies-full-stack)

---


