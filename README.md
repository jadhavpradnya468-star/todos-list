# 📝 React Todo List App

A simple **Todo List Web Application** built using **React.js**.
This application allows users to add, delete, and manage their daily tasks easily.

The app uses **React Hooks**, **React Router**, and **Local Storage** to store todos so they persist even after refreshing the page. Todo apps are commonly used as beginner React projects to demonstrate adding, deleting, and managing tasks in a clean UI. ([Opensource.com][1])

---

# 🚀 Features

* ➕ Add new todos
* ❌ Delete todos
* 💾 Store todos in browser **localStorage**
* 🔁 Persistent data after page refresh
* 🧭 Multiple pages using **React Router**
* ℹ️ About page

---

# 🛠️ Tech Stack

* **React.js**
* **JavaScript (ES6)**
* **React Router**
* **HTML5**
* **CSS3**

---

# 📂 Project Structure

```
todos-list/
│
├── public/
│
├── src/
│   ├── MyComponents/
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── Todos.js
│   │   ├── AddTodo.js
│   │   └── About.js
│   │
│   ├── App.js
│   ├── index.js
│   ├── App.css
│
├── package.json
└── README.md
```

---

# ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/jadhavpradnya468-star/todos-list.git
```

### 2️⃣ Go to project directory

```bash
cd todos-list
```

### 3️⃣ Install dependencies

```bash
npm install
```

### 4️⃣ Start the development server

```bash
npm start
```

The application will run on:

```
http://localhost:3000
```

---

# 📸 Application Pages

### 🏠 Home Page

* Add new todos
* View todo list
* Delete todos

### ℹ️ About Page

* Information about the application

---

# 🧠 How It Works

* Todos are stored in **React state using `useState`**
* Data persistence is handled using **`localStorage`**
* When the app loads, stored todos are fetched from **localStorage**
* React Router handles navigation between **Home** and **About** pages.

---
Live Demo of My APP:
link:https://jadhavpradnya468-star.github.io/todos-list/
# 📌 Future Improvements

* ✔ Edit todo feature
* ✔ Mark todo as completed
* ✔ Dark mode
* ✔ Backend integration (MongoDB / Firebase)
* ✔ Authentication

---
