# 🧠 ResumeIQ – AI-Powered Resume Analyzer

[Live Link 🔗](https://resume-iq-rho.vercel.app/) &nbsp;&nbsp;|&nbsp;&nbsp; [GitHub](https://github.com/SudhirSingh62/ResumeIQ)

## 💼 AI-Powered Resume Analyzer – Smarter Hiring Starts Here

**ResumeIQ** is a full-stack, AI-driven resume analysis platform designed to streamline the hiring process. It intelligently evaluates resumes, provides actionable ATS-based feedback, and matches candidates with relevant job roles — all in real time.

With a clean, modern UI and seamless user experience, ResumeIQ empowers **job seekers** to craft optimized resumes and enables **recruiters** to identify the best-fit candidates faster.

## 🚀 Live Link

🔗 [Visit ResumeIQ](https://resume-iq-rho.vercel.app/)

> Note: Initial load might take a few seconds on free hosting.

---

## 📂 Project Structure
```
ResumeIQ/
├── app/
│ ├── components/ # Reusable UI components (ATS, Accordion, Summary, ScoreGauge, etc.)
│ ├── routes/ # App routes (auth, upload, resume, home)
│ ├── lib/ # Utility logic (PDF to image, Puter integration)
│ ├── root.tsx # App entry point
│ ├── routes.ts # Route definitions
│ ├── app.css # Global styles
├── constants/ # Static values/constants
├── types/ # TypeScript declarations
├── public/ # Static assets (images, icons, workers)
```
---

## 🚀 Features

- 📄 Upload and store resumes (PDF)
- 🤖 AI-based resume analysis with ATS scoring
- 🧠 Summary and section-level feedback
- 🔐 Seamless authentication (built entirely using **Puter.js**)
- 💾 PDF-to-image conversion using server-side logic
- 🧩 Fully modular & reusable component architecture

---

## 🧠 Powered by Puter.js

Instead of a traditional backend, `ResumeIQ` uses **Puter.js** to run **loaders**, **actions**, and **server utilities** natively — directly in your frontend project. This hybrid approach allows:

- 🔐 Built-in auth with no external services
- 🌐 Server logic colocated with routes
- ⚡ Simpler deployment with fewer moving parts

> ✨ Think of it as backend logic without maintaining a backend server — thanks to Puter.

---

## 🛠️ Tech Stack

### Frontend
- ⚛️ **React + Vite** – Fast, modern SPA setup
- ⚙️ **TypeScript** – Type-safe codebase
- 🎨 **Tailwind CSS** – Utility-first styling
- 🧭 **React Router** – Nested routing system
- 📦 **Zustand** – Lightweight global state management

### Backend (via Puter.js)
- 🔐 Authentication and session management
- 🔄 Loaders and actions for dynamic routing
- 🧠 Integration-ready server utilities (e.g., PDF parsing)
---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/SudhirSingh62/ResumeIQ.git
cd ResumeIQ
```
### 2. Install dependencies
```bash
npm install
```
### 3. Start the development server
```bash
npm run dev
```
<p align="center">
  Made with ❤️ by <a href="https://github.com/SudhirSingh62">Sudhir Singh</a> · 
  <a href="https://www.linkedin.com/in/sudhir-singh-840603250/">LinkedIn</a>
</p>
