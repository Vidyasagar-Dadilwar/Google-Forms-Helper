# Google Forms Helper

AI-powered Chrome extension to help you answer Google Forms and Coursera quizzes with ease!

---

## 🚀 Overview

**Google Forms Helper** is a Chrome extension that uses Google Gemini AI to analyze and answer questions in Google Forms and Coursera quizzes. It can automatically fill in answers, highlight correct options, and even auto-fill your personal information (like name, email, etc.) securely from your saved settings.

---

## ✨ Features

- **AI-Powered Answers:** Uses Gemini AI to analyze form/quiz questions and suggest or fill in the best answers.
- **Personal Info Autofill:** Securely stores and fills your personal details (name, email, etc.) only on your device.
- **One-Click Analyze:** Just click "Analyze Form & Mark Answers" to get instant help.
- **Visual Highlighting:** Marks the answers it fills for easy review.
- **Modern UI:** Clean, sidebar-based popup for easy navigation and settings.
- **Supports:**
  - Google Forms (https://docs.google.com/forms/)
  - Coursera Quizzes (https://*.coursera.org/)

---

## 🛠️ How It Works

1. **Extracts questions** from the active Google Form or Coursera quiz.
2. **Sends questions** to Gemini AI using your API key.
3. **Fills in answers** and highlights them in the form/quiz.
4. **Overrides personal info fields** with your saved details (so your real info is always used, not generic AI guesses).

---

## 📦 Installation & Setup

### 1. Clone or Download
- Download this repository as a ZIP and extract it, or clone it using Git:
  ```
  git clone https://www.github.com/Vidyasagar-Dadilwar/Google-Forms-Helper
  ```

### 2. Load as Unpacked Extension
1. Open Chrome and go to `chrome://extensions`.
2. Enable **Developer mode** (toggle in the top right).
3. Click **Load unpacked**.
4. Select the folder where you extracted/cloned this project (the folder containing `manifest.json`).
5. The "Google Forms Helper" icon should now appear in your Chrome extensions bar.

---

## 📝 Usage Guide

### 1. Get a Gemini API Key
- You need a Google Gemini API key. [Get one here](https://aistudio.google.com/app/apikey) (requires Google account and access).

### 2. Open the Extension
- Click the "Google Forms Helper" icon in your Chrome toolbar.

### 3. Enter Your API Key
- Go to the **API Key** section in the sidebar.
- Paste your Gemini API key and click **Save API Key**.

### 4. (Optional) Save Personal Info
- Go to the **Personal Info** section.
- Fill in your details (name, email, etc.) and click **Save**.
- This info is stored **locally** and only used to fill forms for you.

### 5. Analyze a Form or Quiz
- Navigate to a Google Form or Coursera quiz in your browser.
- Open the extension popup and go to the **Analyze** section.
- Click **Analyze Form & Mark Answers**.
- The extension will:
  - Extract questions
  - Ask Gemini for answers
  - Fill in answers and highlight them
  - Override personal info fields with your saved details

---

## 🌐 Supported Sites
- Google Forms: `https://docs.google.com/forms/*`
- Coursera Quizzes: `https://*.coursera.org/*`

---

## 🔒 Permissions
- `activeTab`, `scripting`, `storage`, `tabs`: For injecting scripts, storing your info, and interacting with the current page.
- Host permissions for Google Forms, Coursera, and Gemini API endpoints.

---

## 📝 Notes
- Your API key and personal info are stored **locally** in your browser and never sent anywhere except to Gemini for answering questions.
- This extension is for educational and productivity use. Always review answers before submitting any form or quiz.

---

## 📧 Feedback & Issues
- Found a bug or have a feature request? Open an issue or contact the maintainer.