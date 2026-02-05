Markdown

# 💻 Kashela Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

## 📋 Project Overview

The client-side interface for **Kashela**, an AI-powered financial assistant for African traders. This Single Page Application (SPA) provides an intuitive dashboard for tracking finances, recording transactions via voice, and scanning receipts.

Built with **React**, **Vite**, and **Tailwind CSS** for high performance and responsiveness.

---

## 🚀 Key Features

* **🎙️ Voice Command UI:** Dedicated interface for logging expenses via the Web Speech API.
* **📷 OCR Scanner:** Integrated camera/upload component using Tesseract.js for receipt scanning.
* **📈 Interactive Dashboard:** Visual Profit & Loss charts and financial summaries.
* **📱 Mobile-First Design:** Fully responsive layout optimized for mobile traders.
* **🔐 Auth Integration:** Secure login and registration flows connected to Supabase.

---

## 🛠️ Tech Stack

| Tool | Purpose |
| :--- | :--- |
| **React** | Component-based UI library |
| **Vite** | Next-generation frontend tooling (Fast HMR) |
| **Tailwind CSS** | Utility-first CSS framework for styling |
| **Web Speech API** | Native browser API for Voice-to-Text |
| **Tesseract.js** | Browser-based OCR for image text extraction |

---

## ⚙️ Installation & Setup

### 1. Navigate to Frontend Directory
```bash
cd Kashela/frontend
2. Install Dependencies
Bash

npm install
3. Environment Setup
Create a .env file in the frontend root (if required for API URLs):

Code snippet

VITE_API_URL=http://localhost:8000
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_key
🏃‍♂️ Running the Application
Development Mode
Start the local development server:

Bash

npm run dev
# OR depending on your package.json script:
npm start
The app will run at http://localhost:5173 (default Vite port).

Production Build
To create an optimized production build:

Bash

npm run build
📂 Project Structure
Plaintext

frontend/
│
├── public/             # Static assets (icons, manifest)
├── src/
│   ├── components/     # Reusable UI components (Buttons, Cards)
│   ├── pages/          # Full page views (Dashboard, Login, Scanner)
│   ├── services/       # API calls to Backend & Supabase
│   ├── App.jsx         # Main application component
│   └── main.jsx        # Entry point
├── index.html          # HTML template
├── tailwind.config.js  # Tailwind configuration
├── vite.config.js      # Vite configuration
└── package.json        # Dependencies and scripts
