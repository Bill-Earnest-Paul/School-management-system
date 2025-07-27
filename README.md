# 🎓 Full-Stack School Management System

A full-stack web application for managing students, staff, and events in a school. Built with **React** on the frontend and **Node.js/Express** on the backend, using **MongoDB** as the database.

---

## 📁 Project Structure

project-root/
├── frontend/ # React-based UI
├── backend/ # Node.js/Express API
└── README.md # This file

---

## 🚀 Features

- 🧑‍🎓 Student Registration with auto-generated ID based on class & year
- 🧑‍🏫 Staff Registration with dynamic role assignment
- 🧩 Master Modules:
  - ➕ Add Standards (Classes)
  - ➕ Add Roles (Designations like Teacher, Admin, etc.)
  - 📅 Add Events (used in calendar view)
- 📅 Event Scheduling with calendar integration
- 📊 Dashboard with charts for student distribution & upcoming events
- 🔍 Search, Pagination, and Filtering for student & staff listings
- 🗃️ Reusable master data across forms

---

## 🧩 Master Data Management

- **Standards (Classes):** Add and manage academic classes (e.g., Grade 1–10).
- **Roles (Designations):** Define roles such as Teacher, Principal, Admin Staff, etc.
- **Events:** Add school-wide events that appear on the dashboard calendar.

These master entries are selectable in dropdowns when registering students or staff.

---

## 🛠️ Tech Stack

| Frontend           | Backend           | Database     |
|--------------------|-------------------|--------------|
| React.js           | Node.js + Express | MongoDB      |
| Axios              | REST API          | Mongoose     |
| React Router       |                   |              |
| Recharts / Chart.js|                   |              |

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2. Setup Frontend
    cd frontend
    npm install
    npm start
        Runs on: http://localhost:3000

3. Setup Backend
    cd backend
    npm install
    npm run dev
        Runs on: http://localhost:5000

🛡️ Environment Variables (backend/.env)

Create a .env file in your backend folder with:
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret  # (optional – in case JWT is implemented later)

