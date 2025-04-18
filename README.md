# 💼 Job Portal with Integrated Chatbot – Full Stack Web Application

## 📌 Project Overview

This is a **Full Stack Job Portal Web Application** that allows:

- 👤 **Employers** to **post job opportunities**.
- 🔎 **Job Seekers** to **search, browse, and apply** for jobs.
- 🤖 A built-in **Chatbot** provides assistance by answering job-related queries such as job roles, application steps, and company details.

This platform simplifies the recruitment process while offering real-time help to users via the chatbot.

---

## 🚀 Key Features

### 👨‍💼 Employers:
- Employer Registration & Login
- Post new job listings
- Edit or delete existing jobs
- View all posted job listings

### 👨‍💻 Job Seekers:
- Register & login securely
- Browse all job listings
- Filter by category, location, and role
- Apply to jobs directly
- View applied jobs

### 🤖 Integrated Chatbot:
- Answers questions such as:
  - "What jobs are currently open?"
  - "How do I apply for a developer role?"
  - "What companies are hiring?"
  - "What are the top-paying jobs?"
- Helps users navigate the portal efficiently
- Responds in real-time

---

## 🛠️ Tech Stack

### 🖥️ Frontend:
- HTML5
- CSS3
- JavaScript
- React.js (or Vanilla JS depending on your setup)

### 🗄️ Backend:
- Node.js
- Express.js

### 🗃️ Database:
- MongoDB (with Mongoose for schema modeling)

### 🌐 Other Tools:
- JWT for Authentication
- Multer for file uploads (optional)
- RESTful APIs
- CORS and Helmet for security
- Postman for API testing

---

## 📬 API Endpoints (Examples)

### 🔐 Authentication
- `POST /api/auth/register` – Register user
- `POST /api/auth/login` – Login user

### 💼 Jobs
- `GET /api/jobs` – Get all jobs
- `POST /api/jobs` – Post a new job (Employers only)
- `PUT /api/jobs/:id` – Edit a job
- `DELETE /api/jobs/:id` – Delete a job

### 📥 Applications
- `POST /api/apply` – Apply to a job
- `GET /api/applied-jobs` – View job applications

---

## 🧠 Chatbot Capabilities

Your AI chatbot can answer:
- ✅ Available job roles and companies
- 📌 Application procedures
- 💸 Salary-related queries
- 🧾 Job descriptions and required skills
- 🔍 Navigation help within the website

---

## 🧪 Testing

You can use [Postman](https://www.postman.com/) to test backend APIs like login, job posting, and applications.

---

## 🔧 Setup & Installation

### Prerequisites:
- Node.js installed
- MongoDB running locally or via MongoDB Atlas
- npm (Node Package Manager)

