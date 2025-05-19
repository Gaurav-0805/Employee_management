# 🧑‍💼 Employee Management System 📊

The **Employee Management System** is a modern full-stack web application designed to help organizations efficiently manage employee records, track daily attendance, and gain actionable insights through dynamic charts. It provides a responsive and secure interface for administrators to handle all core HR functionalities in one place.

---

## 🔗 GitHub Repository  
👉 [https://github.com/Gaurav-0805](#) <!-- Replace # with the actual URL of your GitHub repo -->

---

## 🚀 Features

### 👩‍💼 Admin Functionality
- Full-featured **Admin Dashboard** with an intuitive sidebar for navigation.
- Ability to **Add, View, and Delete Employees** with complete details including:
  - Name  
  - Department  
  - Email  
  - Role/Designation

### 📅 Attendance Management
- Daily attendance tracking for each employee.
- Interface to mark employees **Present** or **Absent** for each workday.

### 📊 Visual Analytics
- **Pie Chart**: Department-wise employee distribution.
- **Bar Chart**: Daily attendance count per department.
- Built with `ng2-charts` (Chart.js) for smooth, interactive visuals.

### 🔐 Secure Authentication
- **JWT-based login** system to ensure secure and role-based access.
- Only authenticated users (Admins) can manage employee records and attendance.

### 💡 Additional Highlights
- Clean and responsive UI using **Angular Material**.
- Easy-to-use layout for desktop and mobile screens.
- Modular folder structure for scalability and maintainability.

---

## 🛠 Tech Stack

### 🖥 Frontend
- [Angular](https://angular.io/)
- TypeScript
- HTML & CSS
- [ng2-charts (Chart.js)](https://valor-software.com/ng2-charts/)

### 🗄 Backend
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- `pg` (node-postgres)
- JWT (JSON Web Token) for secure authentication

---

## 📂 Folder Structure

employee-management/
├── backend/
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ ├── middleware/
│ └── index.js
├── frontend/
│ └── src/
│ ├── app/
│ │ ├── components/
│ │ ├── services/
│ │ └── pages/
│ └── index.html
├── README.md
└── .env


---

## 📌 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Gaurav-0805/employee-management-system.git
cd employee-management-system

2️⃣ Backend Setup

cd backend
npm install
# Create a .env file with your DB connection string and JWT secret
node index.js

3️⃣ Frontend Setup

cd frontend
npm install
ng serve

