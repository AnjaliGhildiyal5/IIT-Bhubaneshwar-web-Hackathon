# IIT-Bhubaneshwar-web-Hackathon
Web Hackathon submission for IIT Bhubaneswar. Built with React + Vite, Tailwind CSS, Node.js + Express, and MongoDB. Deployed using Vercel and Render.


#  QuestForge

> Turn your real-life goals into quests, earn XP, track your progress, and level up.

QuestForge is a gamified productivity and personal growth application that transforms everyday tasks and goals into RPG-style quests.

Instead of simply maintaining a traditional to-do list, QuestForge lets users create quests, complete them, earn experience points (XP), and track their progress as they build better habits and accomplish their goals.

---

##  Live Demo

### QuestForge Website

https://iit-hackathon-i745.onrender.com
---

##  Features

-  User authentication
-  Create and manage quests
-  Add quest descriptions
-  Assign quest difficulty
-  Earn XP by completing quests
-  Mark quests as completed
-  Delete quests
-  Stopwatch timer
-  Countdown timer
-  Persistent data storage with Supabase
-  Deployed frontend and backend
-  Responsive and interactive interface

---

##  How QuestForge Works

QuestForge follows a simple RPG-inspired productivity system:

##  Application Workflow

## How QuestForge Works

QuestForge follows a simple RPG-inspired productivity system.

```mermaid
flowchart TD
    A["Open QuestForge"] --> B["Sign Up / Login"]
    B --> C["Dashboard"]

    C --> D{"Choose Action"}

    D --> E["Create Quest"]
    E --> F["Add Description"]
    F --> G["Choose Difficulty"]
    G --> H["Save Quest"]

    H --> I["View Active Quests"]
    I --> J{"Complete Quest?"}

    J -->|No| I
    J -->|Yes| K["Mark Quest Completed"]
    K --> L["Earn XP"]
    L --> M["Update Progress"]
    M --> N{"Level Up?"}

    N -->|Yes| O["Level Up"]
    N -->|No| I
    O --> I

    C --> P["Stopwatch"]
    C --> Q["Countdown Timer"]

    I --> R["Delete Quest"]
    R --> I

    H --> S[("MongoDB")]
    M --> S
```
The goal is to make productivity more engaging by turning real-world activities into game-like challenges.


## Tech Stack

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

### Backend

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
</p>

### Database

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
</p>

### Deployment & Version Control

<p>
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</p>

### Deployment

- Render
- GitHub

---

## Project Structure

```text
IIT-HACKATHON/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   └── services/
│   ├── public/
│   ├── .env
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── config/
│   ├── middleware/
│   ├── auth.js
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── .gitignore
└── README.md
```
---

##  Local Installation

### 1. Clone the repository

```bash
git clone https://github.com/Mohit-web8516/IIT-HACKATHON.git
