# MyFullStack1 App

![GitHub Repo Size](https://img.shields.io/github/repo-size/username/myfullstack1-app)
![GitHub](https://img.shields.io/github/license/username/myfullstack1-app)
![GitHub last commit](https://img.shields.io/github/last-commit/username/myfullstack1-app)
![GitHub issues](https://img.shields.io/github/issues/username/myfullstack1-app)

---

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [API Endpoints](#api-endpoints)
- [Features](#features)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

---

## Project Overview
**MyFullStack1 App** is a **full-stack web application** with a backend built using **Node.js + Express** and a frontend built using **React**.  

The project implements a **Minimal Viable Product (MVP)**, focusing on learning full-stack integration, API development, and project structuring.  

### MVP Phases Implemented
- **Phase 0:** Planning & Repository Setup  
  - Created `frontend/` and `backend/` folders  
  - Initialized GitHub repo  
  - Added `.gitignore` to exclude `node_modules/` and `.env`

- **Phase 1:** Backend Bootstrap  
  - Set up Express server  
  - Installed essential packages: `express`, `cors`, `dotenv`, `axios`, `multer`, `openai`  
  - Configured `nodemon` for hot reloading  
  - Created `index.js` with a simple test route

- **Phase 2:** Topic API & Static Topic Store  
  - Added `data/topics.json` containing an array of topics  
  - Created GET endpoint `/api/topic` that returns a random topic  

---

## Tech Stack
- **Frontend:** React  
- **Backend:** Node.js, Express  
- **API & HTTP Requests:** Axios  
- **File Uploads:** Multer  
- **Environment Variables:** Dotenv  
- **Dev Tools:** Nodemon, VS Code  

---

## Folder Structure
myfullstack1-app/
│
├─ backend/
│ ├─ data/
│ │ └─ topics.json
│ ├─ routes/
│ ├─ index.js
│ └─ .env
│
├─ frontend/
│ └─ src/
│
├─ .gitignore
├─ package.json
├─ package-lock.json
└─ README.md

yaml
Copy
Edit

---

## Getting Started

### Prerequisites
- Node.js v14+  
- npm or yarn  
- Optional: Postman or Browser for API testing  

---

### Backend Setup
1. Navigate to backend folder:

2. Install dependencies:

3. Start server in development mode:

4. Test API endpoint:
GET http://localhost:5000/api/topic


---

### Frontend Setup
1. Navigate to frontend folder:

2. Install dependencies:

3. Start frontend:


**API Endpoints**
Method	Endpoint	Description
GET	/api/topic	Returns a random topic string

**Features**
1. Fully structured full-stack project

2. Express server capable of handling API requests

3. Random topic generator API endpoint

4. .gitignore to ignore unnecessary and sensitive files

5. Modular folder structure for easy scalability

**Future Enhancements**
1. Implement React frontend to display topics dynamically

2. Add user authentication (signup/login)

3. Replace static JSON with database support (PostgreSQL/MySQL)

4. Integrate OpenAI API for dynamic topic suggestions

5. Add unit and integration testing

6. Deploy project using Heroku, Vercel, or AWS

**Author**
M.selya dharsnee – Full-Stack Developer

GitHub: https://github.com/selya911

LinkedIn: https://www.linkedin.com/in/username

Email: selyadharsneem.24mca@kongu.edu


