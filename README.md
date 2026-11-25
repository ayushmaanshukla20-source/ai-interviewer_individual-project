# INTERVIEWAI – Your Personal AI Interviewer

> **"Practice Smarter. Interview Better. Get Hired."**

A modern, professional **AI Mock Interviewer Web Application UI Prototype** built strictly using **HTML5 and CSS3** (zero JavaScript, zero external frameworks, and zero third-party dependencies).

Designed with inspiration from modern developer platforms (Linear, Vercel, Notion), INTERVIEWAI simulates the entire candidate journey—from selecting a target role and configuring simulation parameters to stepping into a live video room and reviewing a detailed 100-point performance report.

---

## 🌟 Key Features

- **Split-Screen Video Interview Stage**: Resembles real commercial video interview platforms with a CSS-illustrated AI Interviewer avatar (animated audio headset, pulsing soundwaves, and eye blinking) alongside a simulated candidate webcam feed with audio level indicators.
- **Pure CSS Analytics & Visualizations**: Interactive 5-session score progression bar chart with CSS `:hover` tooltips, circular `conic-gradient` readiness gauges, and skill competency progress meters.
- **Role-Specific Tracks**: 11 supported software and data roles (Frontend, Backend, Full Stack, AI Engineer, Data Scientist, ML Engineer, Java, Python, Cybersecurity, and DBA).
- **Curated Question Library**: Categorized questions across Technical (JavaScript Runtime, Java JVM, Python GIL), Fundamental CS (DSA, B+ Tree Indexing, OS Threading), AI/ML (Transformers & Attention), HR Rounds, and Behavioral questions formatted using the **STAR** method (*Situation, Task, Action, Result*).
- **Comprehensive Evaluation Report**: Detailed performance assessment covering Technical Knowledge (90%), Communication Clarity (85%), Answer Relevance (92%), and Response Depth (82%) with expandable question-by-question reviews.
- **Fully Responsive & Accessible**: Fluid CSS Grid and Flexbox layouts optimized across desktop, laptop, tablet, and mobile displays.

---

## 📂 Project Structure

```text
interviewai/
│
├── index.html          # Landing Page & Platform Overview
├── dashboard.html      # Candidate Analytics, History & CSS Bar Charts
├── setup.html          # Interview Configuration & Simulation Parameters Form
├── interview.html      # Simulated Live Video Interview Room (AI Avatar & Webcam)
├── questions.html      # Curated Question Bank with Expandable Model Answers
├── results.html        # Comprehensive Evaluation Report & Competency Scoring
├── features.html       # Architectural Feature Deep-Dive & Capabilities
│
└── css/
    ├── style.css       # Master Design System, Color Tokens & Components
    ├── dashboard.css   # Dashboard Grid, Profile Card & Pure CSS Bar Chart
    ├── interview.css   # Video Feeds, AI Speaking Waves & Timer Layout
    ├── results.css     # Conic-Gradient Score Dials & Accordion Reviews
    └── responsive.css  # Mobile, Tablet & Desktop Breakpoint Media Queries
```

---

## 💻 Tech Stack & Design System

- **Markup**: Pure HTML5 (Semantic elements: `<header>`, `<main>`, `<section>`, `<aside>`, `<footer>`, `<details>`, `<summary>`, `<form>`)
- **Styling**: Pure CSS3 (CSS Variables, Flexbox, CSS Grid, Conic Gradients, Media Queries)
- **Animations**: CSS Keyframes (`@keyframes waveBar`, `@keyframes mouthTalk`, `@keyframes audioDetect`, `@keyframes pulseAnimation`)
- **Typography**: Google Fonts (*Plus Jakarta Sans* & *Inter*)
- **Icons**: Inline SVG icons (crisp, zero runtime scripts)
- **Zero JavaScript**: No `<script>` tags, no frontend frameworks (React/Vue/Angular), no external bundlers, and no paid APIs.

---

## 🚀 Getting Started

Since INTERVIEWAI is a pure frontend application, it runs natively in any modern web browser without needing any build steps or package managers.

### Option 1: Direct File Access
Simply double-click or open `index.html` in your browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

### Option 2: Local HTTP Server (Python)
If you prefer running it on a local server:

```bash
# Clone the repository
git clone https://github.com/ayushmaanshukla20-source/ai-interviewer_individual-project.git

# Navigate to the project directory
cd ai-interviewer_individual-project

# Start a local static server
python -m http.server 3000
```
Then visit **`http://localhost:3000`** in your browser.

---

## 📌 Demonstration Notice

This project is developed as an academic / university frontend UI prototype. All interview scores, metric graphs, and speech recognition indicators represent static demonstration data powered entirely by HTML5 and CSS3.

---

## 📄 License

MIT License. Free for educational and personal mock interview practice use.
