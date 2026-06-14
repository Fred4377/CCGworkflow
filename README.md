# CCGworkflow ⚙️

Hello! 👋 This is CCGworkflow, a Kanban-style workflow management tool I built to learn TypeScript, manage nested React state, and practice building interactive project boards.

## 📸 Preview
![CCGworkflow Preview](screenshots/preview.png)

## Why I built this
I built this project because I wanted to transition from pure JavaScript to TypeScript and understand static typing in React. A Kanban board was the perfect project for this because of the complex data structures (columns holding arrays of task objects). Figuring out type safety for draggable components and column transitions was a headache, but TypeScript definitely saved me from a lot of runtime bugs!

## Features
- Kanban Board columns (To Do, In Progress, Done)
- Detailed task cards with category labels and descriptions
- Visual progress tracking dashboard
- Clean, modern dark theme with warm gold and amber accents

## Tech Stack
- **Languages:** TypeScript, JavaScript (ES6+)
- **Frontend:** React, HTML5, CSS3
- **Tools:** Git, Vite

## Known Issues (// TODOs)
- **Drag and Drop:** The drag-and-drop mechanics are currently simulated through button actions. I'm working on integrating a native drag-and-drop library (like `@hello-pangea/dnd`) for smooth card dragging.
- **Local Storage:** The board resets when you refresh. I need to write a quick `useEffect` hook to persist tasks in `localStorage` or hook it up to a backend database.
- **Task Assignments:** Add team member avatars and assign tasks to specific users.

## Setup Instructions

To run this project locally:

1. Clone the repository
2. Run `npm install` in the project root to fetch dependencies
3. Run `npm run dev` to start the development server
4. Open your browser to the local URL displayed in the terminal

Enjoy collaborating! 🚀
