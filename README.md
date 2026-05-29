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

Built by a Academia Student as a school project.  
EduAI-Shield — Controlled AI for Classrooms.
