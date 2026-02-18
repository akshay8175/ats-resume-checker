# 🚀 ATS Resume Checker

A modern AI-powered ATS (Applicant Tracking System) Resume Analyzer built using React, Vite, and TailwindCSS.

This tool analyzes a resume against a job description and generates:

- 📊 ATS Compatibility Score (0–100%)
- ✅ Matched Keywords
- ❌ Missing Keywords
- 💡 Smart Improvement Suggestions
- 📄 PDF Resume Upload Support
- 🌙 Responsive & Clean UI

---

## 🧠 How It Works

The ATS Engine performs:

1. PDF text extraction from resume
2. Job description keyword extraction
3. Stopword removal
4. Case-insensitive keyword matching
5. Score calculation:

---

## 📁 Project Structure

ats-resume-checker/
│
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
│
└── src/
├── main.jsx
├── App.jsx
├── components/
├── utils/
├── hooks/
└── styles/

---

---

## 🏗️ Tech Stack

- ⚛️ React 18
- ⚡ Vite
- 🎨 TailwindCSS
- 📄 pdfjs-dist (PDF parsing)
- 🌐 GitHub Pages Deployment

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/akshay8175/ats-resume-checker.git
cd ats-resume-checker
```

Install dependencies:

> npm install

Run development server:

> npm run dev

