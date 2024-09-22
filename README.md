# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Task Management Application

A React-based task management application that allows users to create, edit, delete, and organize tasks within different boards and lists. The app features drag-and-drop functionality for seamless task movement and reordering, ensuring efficient workflow management.

Predefined Lists: Each board contains predefined lists such as "To Do," "In Progress," and "Done."

Task Management:
Create Tasks: Add new tasks with titles, descriptions, due dates, and assigned users.
Edit Tasks: Modify existing task details.
Delete Tasks: Remove tasks that are no longer needed.
Drag-and-Drop: Intuitive drag-and-drop functionality to move tasks between lists and reorder within the same list.
Persistent Storage: Tasks and boards are saved in localStorage, ensuring data persistence across browser sessions.
Responsive Design: The application is responsive and works seamlessly across various device sizes.

Technologies Used
React: Front-end library for building user interfaces.
React DnD (react-dnd): For implementing drag-and-drop functionality.
UUID (uuid): For generating unique identifiers for tasks.
Tailwind CSS: Utility-first CSS framework for styling.
Local Storage: For data persistence.



INSTALLATION
Follow these steps to set up the project locally:
1) git clone https://github.com/Divian29/task-management-app.git
2) Install Dependencies : Ensure you have Node.js installed. Then, install the necessary npm packages:
npm install
3) The project uses react-dnd for drag-and-drop functionality and uuid for unique IDs. Ensure these are installed:
npm install react-dnd react-dnd-html5-backend uuid
4) Start the Development Server: npm run dev

Project Structure
Here's an overview of the project's file structure
task-management-app/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Board.js
│   │   ├── List.js
│   │   ├── Task.js
│   │   └── TaskForm.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── package.json
├── README.md
└── ...



