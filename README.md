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
| Hosting | GitHub Pages |
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
| <img width="1911" height="1077" alt="image" src="https://github.com/user-attachments/assets/389f33c4-6398-415c-96d2-d213bb360674" <img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/b6960169-aead-4b1e-a058-75894ab01259" <img width="1904" height="1061" alt="image" src="https://github.com/user-attachments/assets/f0044bad-4263-4fd8-84d7-7d47c6c92f62" <img width="1897" height="1072" alt="image" src="https://github.com/user-attachments/assets/8199d85d-dc74-48b2-bebf-ea89dfbd220f" />
 />
 />
 />
 | <img width="1890" height="1067" alt="image" src="https://github.com/user-attachments/assets/735e4b6f-2756-4985-bc83-92b6e3fd298c" />
 |

---

## Author

Built by Levio Probst as a school project.  
EduAI-Shield — Controlled AI for Classrooms.
