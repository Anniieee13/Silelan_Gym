# 🏋️ Silelan Gym – Gym Management System

A full-stack Gym Management System designed to simplify gym operations through a centralized dashboard for managing members, payments, attendance, and daily gym activities.

🌐 **Live Website:** https://silelan-gym.vercel.app

⚙️ **Backend API:** https://silelan-gym.onrender.com

---

## 🚀 Features

- **Owner Authentication:** Secure owner login system.
- **Dashboard:** Overview of total members, today's entries, currently active members, and pending payments.
- **Member Management:** Register and manage gym members.
- **Payment Management:** Track payments and pending membership dues.
- **Attendance Tracking:** Monitor daily gym attendance.
- **Gate Scan:** Dedicated interface for gym entry tracking.
- **Live Overview:** Quick insights into gym activity.

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- REST APIs
- JWT Authentication
- bcryptjs

### Database
- MongoDB
- Mongoose

### Deployment & Tools
- Git & GitHub
- Vercel (Frontend)
- Render (Backend)
- VS Code

## 📂 Project Structure

```text
Silelan_Gym/
│
├── backend/
│   ├── server.js
│   ├── package.json
│   └── ...
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   └── ...
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Anniieee13/Silelan_Gym.git
cd Silelan_Gym
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```env
PORT=10000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
npm start
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
```

Create a `.env` file if your frontend uses the `VITE_API_URL` variable:

```env
VITE_API_URL=http://localhost:10000
```

Start the frontend using the script configured in your `frontend/package.json`.

## 🌍 Deployment

| Component | Platform |
|---|---|
| Frontend | Vercel |
| Backend | Render |
| Database | MongoDB |

## 🔐 Security

- Environment variables are used for sensitive configuration.
- Password hashing with bcryptjs.
- JWT-based authentication.
- Database credentials are not stored in the public repository.

**Never commit `.env` files or expose database credentials and secret keys.**

## 👩‍💻 Developer

**Dhritika Kashyap**

B.Tech – Artificial Intelligence & Machine Learning

GitHub: [Anniieee13](https://github.com/Anniieee13)

---

⭐ If you find this project interesting, consider giving this repository a star!
