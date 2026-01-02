AI-Powered Resume Analyzer with ATS Scoring

A modern AI-driven web application that analyzes resumes using Applicant Tracking System (ATS) principles.
The platform provides structured feedback, scoring, and improvement suggestions to help users optimize their resumes for real-world hiring systems.

The project focuses on combining AI evaluation, frontend system design, and realistic resume screening workflows used in modern recruitment.


## 🚀 Features

- **AI-Powered Resume Analysis:** Homepage of the main

   <img width="1896" height="1017" alt="Homepage" src="https://github.com/user-attachments/assets/61c4270b-c94a-4f0d-97a4-c5331d7b7806" />

- **AI-Powered Resume Analysis:** Upload your resume and receive detailed feedback on ATS compatibility, tone, content, structure, and skills.
  
   <img width="1920" height="1080" alt="Resume upload page" src="https://github.com/user-attachments/assets/64cc2c7d-ffb5-456b-ae2c-1b393e7d44e6" />
   
- **ATS Score:** Instantly see how your resume performs against automated screening systems.

  <img width="1919" height="1029" alt="ATS score result" src="https://github.com/user-attachments/assets/a179f1c6-1710-42ff-8566-8065730d84d0" />
   
- **Actionable Tips:** Get categorized suggestions for improvement, including specific explanations.
   
  <img width="1917" height="1023" alt="Feedback  suggestions page" src="https://github.com/user-attachments/assets/379379a8-1d74-4bf9-8eca-609ed508f96c" />
   
- **Job-Aware Feedback:** Optionally provide job title and description for tailored analysis.
- **Secure File Storage:** All files are managed securely via Puter.js.
- **Authentication:** Sign in/out with Puter.js for a personalized experience.
- **Responsive UI:** Works seamlessly across devices.
- **Data Management:** Wipe all your uploaded data with a single click.

---

## 🛠️ Tech Stack

🌐 Frontend
React 19 – Component-based UI development

TypeScript – Type-safe JavaScript for scalability

Vite – Fast development server and build tooling

React Router v7 – File-based routing, loaders, actions, and SSR-ready architecture

Tailwind CSS – Utility-first styling framework

tw-animate-css – Lightweight animation utilities

Zustand – Simple and efficient global state management

---

## 📦 Project Structure

```
ai-resume-analyzer/
├── app/
│   ├── components/      # Reusable UI components
│   ├── lib/             # Utility libraries (Puter.js, PDF conversion, etc.)
│   ├── routes/          # Route components (home, upload, resume, auth, wipe)
│   ├── app.css          # Tailwind and custom styles
│   └── root.tsx         # App root and error boundary
├── constants/           # Static data and AI prompt templates
├── public/              # Static assets (images, icons, pdf worker)
├── types/               # TypeScript type definitions
├── .react-router/       # React Router build artifacts
├── package.json         # Project scripts and dependencies
├── vite.config.ts       # Vite configuration
└── README.md            # This file
```

---

🤖 AI & Intelligence Layer
Claude Sonnet 4 – Large Language Model used for:
ATS scoring
Resume feedback generation
Skill-gap analysis
Context-aware suggestions
Custom Prompt Engineering – Structured prompts for consistent, explainable AI responses

🧠 Backend / Platform Services
Puter.js – Used as a unified backend platform for:
Authentication (Sign In / Sign Out)
Secure file storage (resume PDFs)
AI service integration
Key-value data storage
Node.js Runtime – Required for development and execution environment

📄 File Handling & Processing
pdfjs-dist – PDF parsing, preview, and text extraction
Client-side PDF processing – Secure handling without exposing raw files

🎨 UI / UX
Responsive Design – Works across desktop, tablet, and mobile
Accessible UI Patterns – Clean layouts and readable feedback
Component-driven architecture – Reusable and maintainable UI components

🧪 Development & Tooling
npm – Dependency management
Git & GitHub – Version control and collaboration
ESLint & TypeScript checks – Code quality and consistency
Modular folder structure – Scalable project organization

🔐 Security & Data Handling
Secure authentication via Puter.js
Controlled file access and storage
User-controlled data wipe functionality
No hardcoded secrets in frontend

🎯 Key Engineering Highlights

ATS-style resume evaluation logic
Structured AI response format
Clean separation of concerns (UI, logic, AI, storage)
Real-world product-style architecture
Resume-ready and internship/project showcase friendly


⚡ Installation & Setup
Prerequisites

Node.js 20+
npm

📥 Clone the Repository
git clone https://github.com/smiteshsp7333/ai-powered-resume-analyzer.git
cd ai-powered-resume-analyzer

📦 Install Dependencies
npm install --legacy-peer-deps


--legacy-peer-deps is required due to React Router v7 peer dependency constraints.

▶️ Run the Development Server
npm run dev

🌐 Open in Browser
http://localhost:5173

developed by- smiteshpokharkar


