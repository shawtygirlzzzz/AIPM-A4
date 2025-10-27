# Project Scope Document

## Objectives
- Develop an AI-based to-do list system that can understand user text input through natural language.  
- Enable users to add, edit, delete, and mark tasks as completed through a chat interface (e.g., Telegram).  
- Integrate a reminder and notification module that alerts users about upcoming or overdue tasks.  
- Enhance user productivity using AI-driven intent recognition and entity extraction.

## Deliverables
- **Telegram Bot with Chat Interface**  
  - Supports natural language task management (add, edit, delete, complete, list, search, reschedule).  
  - Sends reminders and overdue notifications directly to the user.  

- **Streamlit Dashboard**  
  - **Chatbot Page**: Simulated chat or link to Telegram bot.  
  - **Add Task Page**: Form-based task creation with fields (task name, due date, category, status).  
  - **Task List Page**: View, edit, mark as done, or delete tasks.  

- **Backend & Database**  
  - Supabase (Postgres) for task storage.  
  - API layer for task CRUD operations and scheduling reminders.  

- **Reminder & Notification Module**  
  - Scheduler to trigger Telegram alerts for upcoming and overdue tasks. 

## Stakeholders
- **End Users**  
  - Individuals who want a simple, AI-powered task manager accessible via Telegram and dashboard.  

- **Clients**  
  - Project sponsors or academic supervisors (if this is a student project).  

- **Team Roles**  
  - **Project Manager**: Oversees timeline, deliverables, and stakeholder communication.  
  - **Backend Developer**: Implements API, database integration, and reminder logic.  
  - **Bot Developer**: Builds Telegram bot, integrates NLP for intent recognition.  
  - **Frontend Developer**: Designs and develops Streamlit dashboard.  
  - **AI/NLP Engineer**: Implements intent recognition and entity extraction.  


## Tools & Integration

- **MS Project** → For project scheduling, Gantt charts, and milestone tracking.  
- **GitHub** → For version control, issue tracking, and collaborative development.  
- **MS Teams** → For team communication, file sharing, and progress updates.  
- **Supabase** → For database hosting and authentication (if needed).  
- **Telegram Bot API** → For chat-based task management and notifications. 
