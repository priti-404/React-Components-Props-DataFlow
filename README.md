# FocusFlow — React Task Manager

A responsive task management application demonstrating React components, props, state, and one-way data flow.

## Features
- Add tasks with category and priority.
- Mark tasks complete/incomplete and delete tasks.
- Filter all, active, and completed tasks.
- Live statistics and completion progress.
- Responsive desktop and mobile layout.

## React concepts
- **Components:** Header, StatCard, TaskForm, TaskList, TaskItem.
- **Props:** Parent components pass task data and callback functions to children.
- **State:** `useState` stores tasks and the selected filter.
- **Data flow:** App is the single source of truth. Data and callbacks flow down through props; child components invoke callbacks to request state changes.
- **Derived values:** Progress and counts are calculated from state.
- **Lists and keys:** TaskList maps tasks using each task's unique ID.

## Run
Install Node.js, then run:
```bash
npm install
npm run dev
```
To create a production build:
```bash
npm run build
```
Do not upload `node_modules` to GitHub.