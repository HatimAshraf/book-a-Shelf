
# 📘 MERN Book CRUD App

A hands-on playground for anyone diving into the MERN stack. This app lets you manage a collection of books — add, view, edit, and delete them — while exploring how React talks to an Express/Node backend hooked up to MongoDB.

Whether you're learning the stack or brushing up your CRUD skills, this repo is for you.

---

## 🧠 What's Inside

This project shows how to:

- Spin up a backend server using **Express** and **Node.js**
- Connect to a **MongoDB** database using **Mongoose**
- Build a clean UI in **React**
- Wire everything together with **REST APIs**
- Handle basic state management and routing

---

## 🔧 Tech Stack

| Layer        | Tooling                  |
|--------------|---------------------------|
| **Frontend** | React, React Router DOM, Axios |
| **Backend**  | Node.js, Express.js       |
| **Database** | MongoDB + Mongoose        |
| **Dev Tools**| Nodemon, Concurrently     |

---

## 🚀 Getting Started

Make sure you’ve got **Node.js** and **MongoDB** installed.

### 🗂️ 1. Clone this Repo

```bash
git clone https://github.com/HatimAshraf/book-a-Shelf.git
cd book-a-Shelf
````

### 🔌 2. Set up the Backend

```bash
cd backend
npm install
```

Create a `.env` file in `/backend` with:

```
PORT=5000
MONGO_URI=your-mongodb-connection-string
```

Then run:

```bash
npm run dev
```

### 🎨 3. Set up the Frontend

```bash
cd ../frontend
npm install
npm start
```

Visit `http://localhost:3000` in your browser.

---

## 🖼️ What It Looks Like

> Here's a sneak peek (insert your screenshot below):

![Screenshot of App](https://your-screenshot-url.com)

---

## 🛠 Project Structure

```
mern-book-crud/
├── backend/        # Express + MongoDB API
│   ├── models/     # Mongoose schemas
│   └── routes/     # Book API routes
├── frontend/       # React App
│   └── components/ # UI Components
└── README.md
```

---

## 🤔 Why This Project?

There are tons of MERN tutorials, but most skip clarity for speed. This one is made to be:

* **Beginner-friendly** – clean, readable-code
* **Modular** – easy to expand on
* **Realistic** – resembles actual full-stack app architecture

---

## 🙌 Contribute

If you spot a bug or have an idea, feel free to:

* 🍴 Fork the repo
* 🛠 Make your changes
* 📬 Submit a pull request

---

## 📄 License

MIT — use it freely, learn from it, and build cool stuff.

---
