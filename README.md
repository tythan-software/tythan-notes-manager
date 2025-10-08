# Notes Manager 

Helps you organize, categorize, and track your notes. 

---

## Features

- 📝 Add, Edit, Delete Notes with rich-text content
- 🏷️ Tag & Categorize Notes (DSA, System Design, JavaScript, etc.)
- ⭐ Star Important Notes
- 🔍 Search, Filter by Tags/Categories
- 📊 Analytics Dashboard (Notes by Category, Tags Usage, Notes Over Time)
- ☁️ Export Notes as PDF
- 🌐 Responsive UI (Bootstrap + Custom CSS)
- 🔐 JWT Authentication (Register / Login)
- 📡 Global Network Error Handling
- 🛑 Error Boundaries for graceful UI crashes
- 🗂 Pagination (for large notes)
- ⚙️ Built with React, Node.js, Express, MongoDB

---

## Tech Stack

| Frontend  | Backend | Database | Deployment |
|-----------|---------|----------|------------|
| React     | Node.js | MongoDB Atlas | Netlify (Frontend) |
| Bootstrap | Express | Mongoose | Render (Backend API) |

---

## Project Structure

interview-notes-manager/  
|── client/ # React Frontend  
|── server/ # Node.js + Express Backend  
|── README.md

---

## Local Setup Instructions

1. **Setup Backend (Server)**
   ```
    cd server
    npm install
    # Create .env file with MONGO_URI and JWT_SECRET
    npm start

2. **Setup Frontend (Client)**
   ```
    cd client
    npm install
    npm start
  
3. **Access the app at**
   ```
   http://localhost:3000

---

## Screenshots
- Landing Page:
  <img width="1365" height="598" alt="image" src="/screenshots/landing-page.png" />

- Dashboard Analytics:
  <img width="1365" height="602" alt="image" src="/screenshots/dashboard-analytics.png" />

- Notes List with Filters:
  <img width="1362" height="599" alt="image" src="/screenshots/notes-list.png" />

---






