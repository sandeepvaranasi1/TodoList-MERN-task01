# Todo List App

A **simple and intuitive** Todo List application built with **Node.js, Express, React, and MongoDB**. This app allows users to efficiently manage their tasks with features like **CRUD operations, filtering, searching, and editing**.

## 🚀 Features

✅ **Add, View, Update, and Delete (CRUD) Todos**
✅ **Filter Todos** (Completed/Pending)
✅ **Search for Todos** by Title
✅ **Edit Todo Titles** with Inline Editing
✅ **Responsive UI** with Material-UI
✅ **Dark & Light Mode Support** (Optional)

## 🏗 Tech Stack

### **Backend**

- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose ORM**
- **REST API** for CRUD operations

### **Frontend**

- **React.js** with **Material-UI**
- **Redux Toolkit** for State Management
- **TypeScript** for Type Safety (Optional)

## 🚀 Getting Started

Follow these steps to set up and run the project on your local machine:

### 1️⃣ Clone the Repository

```sh
 git clone https://github.com/your-username/todo-list-app.git
 cd todo-list-app
```

### 2️⃣ Install Dependencies

```sh
 npm install
```

### 3️⃣ Set Up Environment Variables

Create a **.env** file in the **backend** folder and add:

```sh
 MONGO_URI=your_mongodb_connection_string
 PORT=5000
```

### 4️⃣ Start the Backend Server

```sh
 cd backend
 npm start
```

### 5️⃣ Start the Frontend

```sh
 cd frontend
 npm start
```

### 6️⃣ Open the App in Your Browser

```
 http://localhost:3000
```

---

## 🌐 API Endpoints

| Method     | Endpoint     | Description                  |
| ---------- | ------------ | ---------------------------- |
| **GET**    | `/todos`     | Get all todo items           |
| **POST**   | `/todos`     | Create a new todo item       |
| **GET**    | `/todos/:id` | Get a single todo item by ID |
| **PUT**    | `/todos/:id` | Update a todo item by ID     |
| **DELETE** | `/todos/:id` | Delete a todo item by ID     |

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. **Fork** the repository
2. Create a **feature branch**
3. **Commit** your changes
4. Submit a **pull request**

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgments

Special thanks to the developers of **Node.js, Express, React, Material-UI, and MongoDB** for their incredible work!

🚀 **Happy Coding!** 🎯
