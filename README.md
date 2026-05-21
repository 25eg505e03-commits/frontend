# Blog App Frontend

Frontend application for a full-stack Blog & Article Publishing Platform built using React and Vite. This application provides a responsive and user-friendly interface for users, authors, and admins to interact with the platform.


# Features

*  User Authentication
*  Role-Based Access

  * Admin
  * Author
  * User
*  Create, Edit & Delete Articles
*  Comment System
*  Category-Based Articles
*  Fast Frontend using Vite
*  React Router Navigation
*  Responsive Design
*  Backend API Integration

---

#  Tech Stack

| Technology       | Usage            |
| ---------------- | ---------------- |
| React.js         | Frontend Library |
| Vite             | Build Tool       |
| React Router DOM | Routing          |
| Axios            | API Requests     |
| Redux            | State Management |
| Bootstrap / CSS  | Styling          |

---

# 📁 Project Structure

```bash
frontend/
│
├── public/
│
├── src/
│   ├── assets/
│   │
│   ├── components/
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── Articles.jsx
│   │   ├── ArticleById.jsx
│   │   ├── AddArticle.jsx
│   │   ├── EditArticle.jsx
│   │   ├── AuthorProfile.jsx
│   │   ├── UserProfile.jsx
│   │   ├── AdminProfile.jsx
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   └── ErrorPage.jsx
│   │
│   ├── redux/
│   │   └── store.js
│   │
│   ├── App.jsx
│   ├── main.jsx
│   ├── App.css
│   └── index.css
│
├── package.json
├── vite.config.js
├── eslint.config.js
└── index.html
```

---

#  Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/25eg505e03-commits/frontend.git
```

## 2️⃣ Move to Project Folder

```bash
cd frontend
```

## 3️⃣ Install Dependencies

```bash
npm install
```

---

# ▶️ Run the Project

```bash
npm run dev
```

Frontend will run at:

```bash
http://localhost:5173
```

---

# Backend Connection

Make sure backend server is running before starting frontend.

Example Backend URL:

```env
http://localhost:4000
```

---

#  Important Packages

```bash
npm install react-router-dom axios redux react-redux
```

---

# Pages & Components

| Component/Page      | Description          |
| ------------------- | -------------------- |
| `Home.jsx`          | Landing page         |
| `Login.jsx`         | User login           |
| `Register.jsx`      | User registration    |
| `Articles.jsx`      | Display all articles |
| `ArticleById.jsx`   | View single article  |
| `AddArticle.jsx`    | Add new article      |
| `EditArticle.jsx`   | Update article       |
| `AuthorProfile.jsx` | Author dashboard     |
| `UserProfile.jsx`   | User dashboard       |
| `AdminProfile.jsx`  | Admin dashboard      |
| `Header.jsx`        | Navigation bar       |
| `Footer.jsx`        | Footer section       |
| `ErrorPage.jsx`     | Error handling page  |

---

#  Authentication

This project supports:

* JWT Authentication
* Protected Routes
* Role-Based Navigation

---

#  Deployment

Frontend deployed using:

* Vercel

Build command:

```bash
npm run build
```
