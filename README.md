
# TaskForge – Smart Team Task Manager

TaskForge is a collaborative task management web app that helps teams organize, assign, and track tasks efficiently.

## Features
- User Authentication (JWT or session-based)
- Task creation, assignment, and tracking
- Kanban-style task board (To Do / In Progress / Done)
- Priority and deadline tagging
- Email reminders using Nodemailer
- Real-time updates using Socket.IO

## Tech Stack
- **Frontend**: React.js + TailwindCSS
- **Backend**: Node.js + Express
- **Database**: MongoDB (with Mongoose)
- **Other**: Socket.IO, Nodemailer

## Folder Structure
```
TaskForge/
├── client/     (React frontend)
├── server/     (Node + Express backend)
└── README.md
```

## Setup Instructions
1. Run `npm install` in both `client` and `server` folders.
2. Create a `.env` file in `server` for DB and JWT configs.
3. Use `npm start` to run both servers.

