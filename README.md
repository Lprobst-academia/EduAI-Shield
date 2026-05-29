# EduAI-Shield

**A controlled AI learning environment for schools.**

EduAI-Shield gives teachers full control over how students use AI — enabling powerful learning while preventing misuse. Built as a single-file web app, it runs in any browser with no installation required.

**Live:** [lprobst-academia.github.io/EduAI-Shield](https://lprobst-academia.github.io/EduAI-Shield)

---

## Features

### For Teachers
- **Student accounts** — Create login credentials for each student. Students cannot self-register.
- **Per-student AI restrictions** — Toggle 10+ AI capabilities individually or globally:
  - Essay / Text Writing
  - Translation
  - Math Solutions
  - Coding
  - Summarizing
  - Definitions & Explanations
  - Spell Check
  - Hints Only Mode
  - Short Answers Only
  - Guiding Questions Mode
  - Step-by-Step Mode
  - Language Lock (force AI to reply in English, German, French, Spanish, Italian, or Dutch)
- **Per-student chat lock** — Lock a single student's chat without affecting the rest of the class.
- **Exam Mode** — Lock all student chats simultaneously with a randomly generated exit code. Regenerate the code at any time to prevent sharing. Each student unlocks individually.
- **Real-time monitoring** — See help requests and copy-paste alerts (>200 characters) instantly.
- **AI Lesson Summary** — Generate a real AI-powered performance report based on actual session data.
- **Print login cards** — Print individual or all student login cards with a clean, ready-to-cut design.
- **Multiple teacher accounts** — Each teacher has their own isolated class.

### For Students
- **Minimalist AI chat** — Clean interface with multiple named conversations per session.
- **Two AI models:**
  - **De Ziggmeister** (Thinking Mode) — Deep, structured, step-by-step answers
  - **Rocky Mountains** (Fast Mode) — Short, direct answers
- **File & image uploads** — Attach images, PDFs, and text files directly in chat.
- **Help button** — Instantly alerts the teacher with a notification.
- **Stays logged in** — Session persists across tab reloads on the same device.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18 (in-browser via Babel) |
| Styling | Custom CSS (no framework) |
| AI | Anthropic Claude API (`claude-sonnet-4-5`) |
| Database | Firebase Realtime Database |
| Hosting | GitHub Pages / Netlify |
| Markdown | marked.js |

---

## Setup

### 1. Firebase
1. Create a project at [firebase.google.com](https://firebase.google.com)
2. Enable **Realtime Database** (test mode)
3. Register a web app and copy the config
4. Replace the `firebaseConfig` object in `index.html`

### 2. Claude API Key
1. Get a key at [console.anthropic.com](https://console.anthropic.com)
2. Open the app → click **Admin** → enter admin password → paste key → **Save API Key**
3. The key is stored in Firebase — all devices use it automatically

### 3. Create a Teacher Account
1. Open the app → click **Admin**
2. Enter admin password: `Peanut`
3. Fill in teacher name and password → **Create Teacher Account**

### 4. Deploy
Upload `index.html` to GitHub Pages or drag it into [netlify.com/drop](https://app.netlify.com/drop).

---

## Passwords & Codes

| What | Value |
|------|-------|
| Admin password | `Peanut` |
| Exam exit code | Generated randomly per session (shown on teacher dashboard) |
| Developer mode | Type `//devmode on` in student chat |
| Dev exam exit | Enter `1234` when in developer mode |

> **Security note:** The admin password and dev mode command should be kept private. Do not share with students.

---

## Project Structure

```
index.html        ← Entire application (single file)
README.md         ← This file
```

---

## Screenshots

| Teacher Dashboard | Student Chat |
|---|---|
| Toggle controls, student cards, exam mode, alerts | Multi-chat tabs, model selector, file upload |

---

## Author

Built by **Sigma (Linus Probst)** as a school project.  
EduAI-Shield — Controlled AI for Classrooms.
