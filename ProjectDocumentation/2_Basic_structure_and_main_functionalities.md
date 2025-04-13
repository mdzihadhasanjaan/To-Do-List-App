# ✅ Project Phase 2 – Basic Structure and Main Functionalities

This phase focuses on building a fully functional full-stack Task Management web application named **TaskMaster**, where users can register, log in, and manage their tasks with deadlines. The system ensures user authentication, real-time task interactions, and cloud-based deployment using **Render**.

---

## 1. 🌐 Environment

- **Frontend Framework:** React (Create React App)
- **Backend Framework:** Express.js (Node.js)
- **Database:** MongoDB Atlas (NoSQL Cloud DB)
- **Hosting:** Render (Free Tier for both Frontend and Backend)
- **Version Control:** Git + GitHub
- **Dev Tools:** VS Code, Postman, MongoDB Compass

---

## 2. 🛠️ Backend

- Built with **Express.js**, modular structure
- RESTful API routes:
  - `POST /register` – Register new user
  - `POST /login` – Login with JWT authentication
  - `GET/POST/DELETE/PATCH /api/tasks` – Task CRUD operations
- Middleware:
  - JWT-based authentication for protected task routes
- Environment config with `.env`:
  - `MONGO_URI`
  - `JWT_SECRET`
- Hosted on Render with Node environment
- CORS properly configured to allow frontend communication

---

## 3. 🎨 Frontend

- Built using **React** with modern component-based structure
- Pages:
  - `Home` – Landing page with navigation
  - `Login` – User login form
  - `Register` – New user registration form
  - `Tasks` – Task dashboard with task list and add form
- State management using `useState` and `useEffect`
- API communication via Axios and Fetch
- Frontend `.env` for backend URL:
  - `REACT_APP_API_URL=https://taskmaster-u7lz.onrender.com`
- Hosted on Render Static Site

---

## 4. 🧩 Database

- MongoDB Atlas (cloud-hosted)
- Collections:
  - `users` – Stores email and hashed passwords
  - `tasks` – Stores task details with reference to user
- Mongoose models:
  - `User` schema
  - `Task` schema

---

## 5. 🏗️ Basic Structure and Architecture


- Separation of concerns maintained
- Backend and frontend deployed separately
- Secure and scalable architecture

---

## 6. ⚙️ Functionalities

- 🧑‍💼 User Registration and Login with JWT
- ✅ Add new tasks with:
  - Title
  - Optional description
  - Date and time input
- 📋 Task list shows all active tasks
- ✔️ Mark task as completed
- 🗑️ Delete any task
- 🔐 Route protection using `PrivateRoute` component
- Persistent login using localStorage token

---

## 7. 📄 Code Quality and Documentation

- Code is modular, readable, and scalable
- Services and API calls are abstracted
- All core components and logic documented with comments
- GitHub repo maintained with regular commits
- README includes deployment links and environment setup

---

## 8. 🧪 Testing and Error Handling

- API tested using **Postman**
- Authentication and protected routes tested
- Form validations for empty inputs
- Try-Catch blocks in async calls to handle failures
- Logs show clean errors for quick debugging
- 404 or token-based errors are handled and shown in frontend

---

## 9. 🖥️ User Interface and Interaction

- Modern UI with minimal and clean design
- Responsive layout
- Intuitive navigation and form design
- Clear task view with buttons: **Mark Done** / **Delete**
- User experience enhanced with:
  - Feedback alerts
  - Input validations
  - Button interactions
- Homepage includes call to action (Go to Tasks / Login)

---

## 🔗 Live App Links

- **Frontend:** [https://taskmaster-frontend-mux4.onrender.com](https://taskmaster-frontend-mux4.onrender.com)
- **Backend:** [https://taskmaster-u7lz.onrender.com](https://taskmaster-u7lz.onrender.com)

---

## 🔗 Backend and frontend github repo: https://github.com/mdzihadhasanjaan/taskmaster-frontend

## 👨‍💻 Author

Md Zihad Hasan Jaan, Boutaghane, Mouadh
Full Stack Developer | Phase 2 Web Development Assignment  
Finland, 2025

