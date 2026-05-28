# Personal Portfolio Website — README.md

## 📌 Project Overview

This is a Full Stack Personal Portfolio Website developed using:

* Frontend: HTML, CSS, JavaScript
* Backend: Node.js with Express.js
* Database: MongoDB
* Architecture: MVC Pattern

The application provides a responsive portfolio website with backend-driven content, contact form handling, REST APIs, and MongoDB database integration.

---

# 🚀 Features

✅ Fully Responsive UI
✅ REST API Integration
✅ MongoDB Database Connectivity
✅ Contact Form with Backend Validation
✅ MVC Architecture
✅ Environment Variable Security
✅ Email Integration Ready
✅ Production Ready Structure

---

# 🛠️ Technologies Used

## Frontend

* HTML5
* CSS3
* JavaScript

## Backend

* Node.js
* Express.js

## Database

* MongoDB Atlas
* Mongoose ODM

## Other Tools

* Nodemon
* Dotenv
* Cors

---

# 📂 Project Structure

```bash
portfolio-project/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md
```

---

# ⚙️ Installation Steps

## 1️⃣ Clone or Download Project

Extract the ZIP file.

---

## 2️⃣ Open Backend Folder

```bash
cd backend
```

---

## 3️⃣ Install Dependencies

```bash
npm install
```

If packages are missing, install manually:

```bash
npm install express mongoose dotenv cors nodemailer nodemon
```

---

# 🔐 Environment Variables

Create a `.env` file inside the backend folder.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
```

---

# 🌐 MongoDB Setup

## Step 1:

Create account in MongoDB Atlas.

## Step 2:

Create Cluster.

## Step 3:

Click "Connect".

## Step 4:

Copy connection string.

Example:

```env
mongodb+srv://username:password@cluster.mongodb.net/portfolio
```

Paste inside `.env`.

---

# ▶️ Run Backend Server

```bash
npm run dev
```

OR

```bash
node server.js
```

Expected Output:

```bash
MongoDB Connected
Server running on port 5000
```

---

# 💻 Run Frontend

Open:

```bash
frontend/index.html
```

in browser.

---

# 📡 API Endpoints

## Contact API

### POST Request

```http
POST /api/contact
```

### Request Body

```json
{
  "name": "Hasini",
  "email": "hasini@gmail.com",
  "message": "Hello"
}
```

---

# 🧩 Future Improvements

* Dark Mode
* Admin Dashboard
* Resume Upload
* Authentication
* Project Management Panel
* Blog Section
* GitHub API Integration

---

# 🚀 Deployment

## Frontend Deployment

* Vercel
* Netlify

## Backend Deployment

* Render
* Railway

## Database

* MongoDB Atlas

---

# 👩‍💻 Author

Developed as a Full Stack Engineering Internship Project.

---

# 📄 License

This project is for educational and internship purposes.
