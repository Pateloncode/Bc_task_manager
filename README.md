# BC_task_manager

Here's a complete `README.md` file for a **Task Management Application** built using **Next.js**, **Tailwind CSS**, and **Express.js API** on the backend:

---

```markdown
# 📝 Task Management Application

A full-stack task management app built with **Next.js** (frontend), **Tailwind CSS** (styling), and **Express.js** (backend API). Users can create, update, delete, and track their tasks in a simple and responsive UI.

---

## 🔧 Tech Stack

### Frontend
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)

### Backend
- [Express.js](https://expressjs.com/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

---

## 📁 Project Structure

project-root/
│
├── fronted/                # Next.js frontend
│   ├── pages/             # Pages and routes
│   ├── components/        # Reusable UI components
│   ├── styles/            # Tailwind CSS configuration
│   └── ...
│
├── backend/                # Express backend
│   ├── routes/            # API routes
│   ├── controllers/       # Route logic
│   ├── models/            # MongoDB models (Mongoose)
│   ├── app.js             # Express app entry
│   └── ...
│
├── .env                   # Environment variables
├── README.md              # Project documentation
└── ...


---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- MongoDB or any other supported database

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/task-manager-app.git
cd BC_task_manager
````

---

### 2. Setup the Backend (Express)

```bash
cd server
npm install
```

* Create a `.env` file in the `server` directory:

```env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/taskmanager
```

* Start the backend server:

```bash
npm run dev
```

> The API will run on `http://localhost:5000`

---

### 3. Setup the Frontend (Next.js)

```bash
cd ../client
npm install
```

* Create a `.env.local` file in the `client` directory:

```env
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```

* Start the frontend server:

```bash
npm run dev
```

> The app will run on `http://localhost:3000`

---

## ✨ Features

* ✅ User-friendly task dashboard
* 🆕 Add new tasks
* 🔄 Update task status (e.g., complete/incomplete)
* 🗑️ Delete tasks
* 📦 RESTful API using Express.js
* 🎨 Responsive UI with Tailwind CSS

---

## 🧪 API Endpoints

| Method | Endpoint         | Description       |
| ------ | ---------------- | ----------------- |
| GET    | `/api/tasks`     | Get all tasks     |
| POST   | `/api/tasks`     | Create a new task |
| PUT    | `/api/tasks/:id` | Update a task     |
| DELETE | `/api/tasks/:id` | Delete a task     |

---

## 🛠️ Contributing

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add your message'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

---

## 📄 License

This project is licensed under the MIT License.

---


Made with ❤️ by Manan

