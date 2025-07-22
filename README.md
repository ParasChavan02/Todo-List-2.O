# ToDo List 2.O

A modern, full-stack To-Do List web application built with Node.js, Express, MongoDB, and EJS. This app allows users to add, view, and delete tasks with a clean, responsive interface.

---

## 🚀 Live Demo

**Try it now:** [https://todo-list-2-o.onrender.com](https://todo-list-2-o.onrender.com)

---

## Features

- Add new tasks to your to-do list
- View all your current tasks
- Delete completed tasks with a single click
- Responsive and modern UI with custom CSS
- Persistent storage using MongoDB Atlas

---

## Screenshots

<!-- Optionally add screenshots here -->

---

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account (or local MongoDB)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd ToDo-List-2.O
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add your MongoDB connection string:
     ```env
     MONGODB_URI=your_mongodb_connection_string
     ```
4. **Start the server:**
   ```bash
   node app.js
   ```
5. **Open your browser:**
   - Visit `http://localhost:8000`

---

## Project Structure

```
ToDo List 2.O/
├── app.js              # Main server file
├── package.json        # Project metadata and dependencies
├── Public/
│   └── css/
│       └── style.css   # Custom styles
├── views/
│   └── index.ejs       # Main EJS template
└── ...
```

---

## Technologies Used
- Node.js
- Express.js
- MongoDB & Mongoose
- EJS (Embedded JavaScript Templates)
- CSS3 (Custom styling)

---

## Author
- **Paras Chavan**

---

## License
This project is licensed under the ISC License.

---

## Acknowledgements
- [Express.js Documentation](https://expressjs.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [EJS Templates](https://ejs.co/) 