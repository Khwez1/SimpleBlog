📘 SimpleBlog - Fullstack Blog App with React + ASP.NET Core

A lightweight blog application built with React (Vite) on the frontend and ASP.NET Core Web API on the backend, using SQL Server and Entity Framework Core for data persistence.

📁 Project Structure

SimpleBlog/
├── backend/           # ASP.NET Core Web API
│   ├── Controllers/
│   ├── Data/
│   ├── Models/
│   └── Program.cs
│
└── frontend/          # React app (Vite)
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   └── App.jsx

🚀 Getting Started

1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/SimpleBlog.git
cd SimpleBlog

2. Setup the Backend

cd backend/SimpleBlog.Api

Install packages:

dotnet restore

Update DB:

dotnet ef database update

Run the server:

dotnet run

Backend runs on http://localhost:5000

3. Setup the Frontend

cd ../../frontend
npm install
npm run dev

Frontend runs on http://localhost:5173

🧠 Features

View blog posts

Add new posts (via API call or future form)

Server-rendered content with SQL persistence

⚙️ Tech Stack

Frontend

React (Vite)

JavaScript

Fetch API

Backend

ASP.NET Core Web API

Entity Framework Core

SQL Server

✅ Prerequisites

.NET 7 SDK or later

SQL Server (Express/Developer)

Node.js + npm

📦 Future Improvements

Authentication (JWT or Identity)

CRUD for posts

Comment system

Admin dashboard

Deployment via Azure or Render

📄 License

This project is licensed under the MIT License.