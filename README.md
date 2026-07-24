# 📚 Provakar Exam Hub

### West Bengal Gram Panchayat 2026 — Bengali, English & Interview Preparation Portal

> **বাংলা ও ইংরেজি — একসাথে, একটাই গন্তব্য**  
> *তোমার পরীক্ষার প্রস্তুতি, এখন তোমার হাতের মুঠোয়।*

[![Live Website](https://img.shields.io/badge/Live%20Website-Open%20Provakar%20Exam%20Hub-0ea5e9?style=for-the-badge)](https://mentor-hub-pro.github.io/bengali-engalish-grammer/)
[![No Framework](https://img.shields.io/badge/Framework-Vanilla%20JavaScript-f7df1e?style=for-the-badge)](#major-features)
[![Free](https://img.shields.io/badge/Access-100%25%20Free-22c55e?style=for-the-badge)](#-free-for-learners)

---

## 🌟 About the Project

**Provakar Exam Hub** is a free, browser-based study portal created for learners preparing for **West Bengal Gram Panchayat–style examinations**. It combines Bengali grammar, English grammar, vocabulary, reading practice, exam-style question banks, standalone chapter handbooks, revision tools, and interview preparation in one place.

The project is designed to run as a static website—there is **no login, no advertisement, no tracking account, and no paid wall**.

> **Important:** Question banks, interview questions, and high-difficulty practice sets are preparation materials. They are **not official WB Gram Panchayat 2026 question papers or guaranteed predictions**.

---

## 🆓 Free for Learners

- No login or signup
- No advertisements
- No paid subscription wall
- No external framework dependency
- Browser-based local study tools
- Free chapter handbooks, PDF printing, and TXT export

---

## 🚀 Live Links

| Resource | Link |
|---|---|
| Main Study Portal | [Open Provakar Exam Hub](https://mentor-hub-pro.github.io/bengali-engalish-grammer/) |
| Handbook Library | `#handbooks` from the main portal |
| Interview Preparation | `#interview` from the main portal |
| Standalone Handbook Index | `handbooks/00-index.html` after deployment |

---

## ✨ Major Features

### Dual Learning Hubs

- 🅱 **বাংলা হাব** — Bengali grammar, vocabulary, literature, and comprehension
- 🇬🇧 **English Hub** — English grammar, vocabulary, reading, and sentence skills
- One shared dashboard, theme system, progress system, notes, bookmarks, quiz engine, and study tools

### Learning & Revision

- Detailed theory and book-mode chapter guides
- Bengali explanations below English grammar rules
- Memory tricks, shortcuts, common traps, and exam focus cards
- Colour-coded formula and memory boards
- Rapid one-line revision examples
- Exam-style Moderate, Hard, and Super Hard question-answer practice
- Flashcards with spaced-repetition behaviour
- Chapter completion tracking

### Study Tools

- 📅 Daily Study Planner
- 🧠 Mistake Notebook
- 📖 Personal Dictionary
- 📝 Notes with copy, cut, print, and local auto-save
- ✍️ Handwriting / practice canvas
- 🍅 Pomodoro Timer
- 🎯 Daily Challenge
- 💎 Word of the Day
- 🔎 Global search across Bengali and English content
- 📊 Progress dashboard and study streaks

### Reading Experience

- Dark / light mode
- Focus reading mode
- Font-size controls
- Full-screen mode
- Back, Home, and Full-screen controls
- Settings panel for reading density, TTS speed, table row count, motion, cursor, and background preferences
- Keyboard shortcut support

### Handbook System

- In-website handbook route for every chapter
- Separate standalone handbook HTML files
- Print / Save as PDF through the browser print dialog
- Plain-text handbook download
- Dark / light mode in standalone handbooks
- Sequential format: **Question → Answer → Reason**

---

## 📖 Chapters

### Bengali Hub — 9 Chapters

1. পদ পরিচয়
2. সন্ধি
3. সমাস
4. কারক ও বিভক্তি
5. প্রকৃতি ও প্রত্যয়
6. শব্দভাণ্ডার
7. বাক্য পরিবর্তন ও সংশোধন
8. বাংলা সাহিত্য
9. বোধপরীক্ষণ

### English Hub — 11 Chapters

1. Parts of Speech
2. Tenses — The Complete System
3. Articles
4. Voice — Active & Passive
5. Narration — Direct & Indirect
6. Vocabulary Treasury
7. Sentence Correction & Transformation
8. Reading Comprehension
9. Gender, Number & Degree
10. Question Tags, Conditionals & Modals
11. Spelling, Punctuation & Word Order

### Additional Preparation Area

- 🎤 **WB Gram Panchayat Interview Preparation**
  - Bengali + English model responses
  - Foundation, situation, ethics, and decision-making questions
  - Easy, Moderate, and Super Hard practice modes

---

## 🗂️ Project Structure

```text
Begali-English-grammer-v2.0/
│
├── README.md
│
├── prabhaker-exam-hub/
│   ├── index.html          # Main single-page portal
│   ├── style.css           # Main design system and responsive styles
│   ├── script.js           # Data, router, quiz, tools, and interactions
│   └── handbooks/          # Standalone handbook pages served by the portal
│       ├── 00-index.html
│       ├── chapter-bn-ch1.html
│       ├── ...
│       ├── chapter-en-ch11.html
│       └── gram-panchayat-interview.html
│
└── provakar-chapter-handbooks/
    └── Optional exported handbook collection
```

> Keep the `handbooks/` directory inside `prabhaker-exam-hub/`. The in-website **Separate File** buttons use this relative path.

---

## ▶️ Run Locally

No package installation is required.

### Option 1 — Open directly

Open:

```text
prabhaker-exam-hub/index.html
```

in a modern browser.

### Option 2 — Use a local static server

```bash
cd prabhaker-exam-hub
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

A local server is recommended for the best LocalStorage, download, and browser feature support.

---

## 🌐 Deploy to GitHub Pages

1. Upload or push the complete `prabhaker-exam-hub/` directory.
2. Ensure these files and folder are present:

```text
index.html
style.css
script.js
handbooks/
```

3. In GitHub repository settings, open **Pages**.
4. Select the branch and correct publishing folder.
5. Save and wait for deployment.
6. Hard refresh after an update:

```text
Ctrl + Shift + R
```

Example commit:

```bash
git add README.md prabhaker-exam-hub
git commit -m "Update Provakar Exam Hub study portal and handbooks"
git push origin main
```

---

## 🧭 How to Study Effectively

### Recommended Chapter Flow

```text
Book Mode Theory
→ Formula / Memory Board
→ 100 Examples
→ High-Difficulty Question & Answer Set
→ Flashcards
→ Chapter Quiz
→ Mistake Notebook Revision
```

### Five-Day Revision Cycle

| Day | Focus |
|---|---|
| Day 1 | Theory + shortcuts |
| Day 2 | Examples + rapid revision |
| Day 3 | Moderate questions |
| Day 4 | Hard / Super Hard questions |
| Day 5 | Mistakes + flashcards + quiz retry |

---

## ⚙️ Settings & Accessibility

The settings panel supports:

- Dark / light preference
- Comfortable / compact reading density
- Table rows per load
- TTS speed
- Animated background toggle
- Custom cursor toggle
- Reduced motion mode
- Auto-bookmarking wrong quiz answers
- Focus reading mode

Accessibility support includes:

- Skip link
- Keyboard navigation
- Focus-visible states
- Reduced-motion support
- Screen-reader labels on interactive controls
- Responsive layouts for mobile, tablet, and desktop

---

## 📝 Personal Data & Privacy

The portal uses browser LocalStorage for optional personal features such as:

- Notes
- Planner tasks
- Bookmarks
- Dictionary entries
- Mistake notebook entries
- Theme and settings preferences
- Chapter progress

No account is required. No personal data is sent to a server by the static website.

> Clearing browser data may clear locally saved notes, planner tasks, bookmarks, and progress.

---

## 🤝 Contributing Content

Suggestions and corrections are welcome, especially for:

- Bengali literature facts
- Grammar explanations
- Typographical errors
- Question quality
- Accessibility improvements
- WB-style exam practice patterns

When suggesting a factual correction, please include a reliable reference or official source where possible.

---

## ⚠️ Disclaimer

This project is an educational practice portal. It does not claim affiliation with the Government of West Bengal or any recruiting authority. All practice questions, interview prompts, and revision material are intended for learning and self-assessment.

---

## ❤️ Built For Learners

Made with care for Bengali-speaking learners and WB competitive-exam aspirants.

**Practice consistently. Revise your mistakes. Build confidence.**
