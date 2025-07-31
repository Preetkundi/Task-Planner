# 📋 MERN Task Manager

A full-stack task management web application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This system is designed to improve productivity, streamline team collaboration, and manage tasks effectively with real-time updates and analytics.

## 🔧 Features

✅ **User Dashboard**  
View assigned tasks, monitor progress, and access personalized task insights.

✅ **Task Management**  
Create, update, delete, and track tasks with due dates, priorities, and checklists.

✅ **Automated Status Updates**  
Status changes dynamically based on checklist completion (e.g., from "In Progress" to "Completed").

✅ **Team Collaboration**  
Assign tasks to multiple users and track individual/team completion rates.

✅ **Priority & Progress Tracking**  
Categorize tasks into High/Medium/Low priority and visualize progress via intuitive UI indicators.

✅ **Task Report Downloads**  
Export task data into CSV/PDF for reporting and tracking.

✅ **Attachments Support**  
Attach and view external links or files related to tasks.

✅ **Mobile Responsive UI**  
Smooth, responsive experience across mobile, tablet, and desktop.

---

## 🛠️ Tech Stack

| Tech         | Description                          |
|--------------|--------------------------------------|
| **Frontend** | React.js, React Router, Tailwind CSS |
| **Backend**  | Node.js, Express.js                  |
| **Database** | MongoDB (Mongoose)                   |
| **Auth**     | JWT Authentication                   |
| **Other**    | Multer (if used), dotenv, etc.       |

---

## 📁 Folder Structure

```bash
.
├── client/              # React frontend
│   ├── components/
│   ├── pages/
│   └── ...
├── server/              # Node.js backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── ...
└── README.md
```

## Clone the Repository
git clone https://github.com/Preetkundi/Task-Planner.git
cd Task-Planner

## Setup Environment Variables
Create a .env file in the server/ directory:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
 ## 4. Run the App
 # In one terminal (backend)
cd server
npm run dev

# In another terminal (frontend)
cd client
npm start


