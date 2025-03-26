
# Project Phase 2 – Basic Structure and Main Functionalities

---

## 1. Environment

The development environment has been set up with the following tools and configurations:

- **Code Editor:** Visual Studio Code (with ESLint and Prettier extensions).
- **Package Manager:** npm (Node Package Manager).
- **Frontend Framework:** React.js via Create React App.
- **Version Control:** Git & GitHub for project tracking and submission.
- **Browser:** Google Chrome with React Developer Tools extension.
- **Design Tool:** Uizard (for UI prototypes).
- **File Structure:** Organized using a modular component-based structure.

These tools were chosen for their flexibility, ease of use, and strong community support. The environment was configured to enable fast development and efficient debugging.

---

## 2. Backend

No backend has been implemented in Phase 2. All task data is currently stored and retrieved from the browser's **LocalStorage**.

This decision was made to keep the application simple and lightweight. However, the application architecture has been designed in a way that will allow seamless backend integration in Phase 3 using Node.js and Express.

---

## 3. Frontend

The frontend is fully developed using **React.js**. The application is broken into multiple reusable and stateful components.

### **Main Components:**
- **App.js** – The main component that handles routing and global state.
- **TaskList.js** – Displays all tasks, both active and completed.
- **TaskItem.js** – Represents a single task with edit/delete/complete options.
- **AddTask.js** – A form for adding a new task.
- **EditTask.js** – Allows users to update an existing task (optional modal-based).

The state is managed using React Hooks (`useState`, `useEffect`). Styling is done using plain CSS (for now).

---

## 4. Database

For this phase, **LocalStorage** is used to store user tasks.

### Sample Task Structure:
```json
{
  "id": "1",
  "title": "Finish React homework",
  "description": "Complete the project setup and component creation",
  "dueDate": "2025-03-24",
  "completed": false
}
