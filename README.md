# 🔗 TinyLink Frontend

**TinyLink** is a simple and elegant dashboard for creating and managing short URLs.  
Users can generate short links, track clicks, and view analytics like the total number of links and last clicked time.

---

## 🌐 Live Demo
👉 [https://tinylink-frontend-2yqq.onrender.com](https://tinylink-frontend-2yqq.onrender.com)

---

## ⚙️ Features
- Create short URLs instantly  
- View all created links in a table  
- Displays total links and total clicks  
- Shows last clicked time (in IST)  
- Delete links  
- Connected to a hosted backend (Render + NeonDB)

---

## 🛠️ Tech Stack
- **HTML5**
- **TailwindCSS**
- **JavaScript (Fetch API)**
- **Backend API:** Render-hosted Express server
- **Database:** Neon PostgreSQL

---

## 🔗 Backend API
Base URL:  
`https://tinylink-backend-tyfm.onrender.com`

Endpoints:
- `GET /api/links` → Fetch all links  
- `POST /api/links` → Create a new short link  
- `DELETE /api/links/:code` → Delete a short link  

---

## 🧩 Related Repository
Backend Code:  
👉 [https://github.com/GayathriSubramani07/tinylink-backend](https://github.com/GayathriSubramani07/tinylink-backend)

