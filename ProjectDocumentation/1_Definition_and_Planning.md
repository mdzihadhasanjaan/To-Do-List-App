# Project Phase 1 – Definition and Planning

---

## 1. User Personas

### Persona 1: Arif Hossain (Student)
- **Age:** 25  
- **Occupation:** University Student  
- **Goals:** Wants to stay organized with study deadlines and exams.  
- **Frustrations:** Often forgets to submit assignments on time.  
- **How the app helps:** Allows task tracking with due dates and reminders.

### Persona 2: Anika Rahman (Working Professional)
- **Age:** 30  
- **Occupation:** Software Engineer  
- **Goals:** Manage both work tasks and personal chores.  
- **Frustrations:** Juggles between multiple project deadlines and forgets personal errands.  
- **How the app helps:** Keeps all tasks in one place with clear priority indicators.

---

## 2. Use Cases and User Flows

### Use Case 1: Add a New Task
- The user opens the app.
- Clicks on "Add Task".
- Fills in task name and optional description.
- Selects due date (optional).
- Saves the task and sees it listed.

### Use Case 2: Complete a Task
- The user checks a box or clicks a button next to a task.
- The task gets marked as completed.
- Visually changes (e.g., strikethrough or moved to "Completed" section).

### Use Case 3: Delete a Task
- The user clicks on a delete icon.
- Confirms deletion in a popup.
- The task is removed from the list.

---

## 3. UI Prototypes

**Wireframes:**
- Home screen with task list and "Add Task" button.
- Add Task form screen.
- Task view/edit screen.

*(Screenshots or links to Figma/Balsamiq designs will be added here later)*

---

## 4. Information Architecture and Technical Design

### Frontend:
- **Framework:** React.js  
- **State Management:** useState, useEffect  
- **Main Components:**
  - `TaskList.js` – displays list of tasks.
  - `TaskItem.js` – displays individual task.
  - `AddTask.js` – form to add new task.
  - `EditTask.js` – update or delete a task.

### Data Handling:
- Tasks will be stored in **LocalStorage** (for now).
- Structure:
  ```json
  {
    "id": "task-id",
    "title": "Task Title",
    "description": "Task description",
    "completed": false
  }

