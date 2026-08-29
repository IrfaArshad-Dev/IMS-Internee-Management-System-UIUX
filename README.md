<div align="center">

# 🎓 IMS — Internee Management System
### UI/UX Case Study

**A complete design system for managing the entire internship lifecycle —
from onboarding to offboarding — in one centralized platform.**

![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Type](https://img.shields.io/badge/type-UI%2FUX%20Design-blueviolet)
![Tool](https://img.shields.io/badge/tool-Figma-orange)
![Screens](https://img.shields.io/badge/screens-79-informational)
![Modules](https://img.shields.io/badge/modules-9-lightgrey)

</div>

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Who Is This For](#-who-is-this-for)
- [Design Process](#-design-process)
- [Modules & Features](#-modules--features)
- [Screens](#-screens)
- [Design System](#-design-system)
- [Tools Used](#-tools-used)
- [My Contribution](#-my-contribution)
- [Key Learnings](#-key-learnings)
- [Team](#-team)
- [Project Files](#-project-files)
- [Contact](#-contact)

---

## 🧭 Overview

**IMS (Internee Management System)** is an enterprise-style internship
management platform designed to replace scattered spreadsheets, email
threads, and manual attendance registers with a single, structured
digital workspace.

The platform gives interns a self-service dashboard to manage their
entire internship journey, while giving supervisors and HR the tools to
track attendance, assign and review tasks, monitor performance, and
issue certificates — all from one system.

> *"Empowering Learning, Growth and Careers."*

This repository documents the full UI/UX design — from problem framing
to a 9-module, 79-screen high-fidelity Figma design.

---

## ❗ Problem Statement

Most internship programs today are run informally:

- Attendance tracked in spreadsheets or WhatsApp check-ins
- Tasks assigned over email or chat, with no central status tracking
- No visibility into an intern's overall progress or performance
- Certificates and completion documents handled manually at the end
- No structured learning resources provided during the internship

**IMS solves this by giving every stakeholder — intern, mentor, and
admin — a single source of truth for the entire internship lifecycle.**

---

## 👥 Who Is This For

| User | What they need from IMS |
|---|---|
| **Intern** | Track tasks, mark attendance, request leave, access learning material, view feedback, request certificates |
| **Mentor / Supervisor** | Assign tasks, review submissions, give feedback, evaluate performance |
| **HR / Admin** | Monitor attendance & progress across interns, manage offboarding, issue certificates |

---

## 🔍 Design Process

1. **Requirement Gathering** — Identified the core internship lifecycle stages: onboarding → daily operations → performance tracking → offboarding
2. **Information Architecture** — Mapped 9 core modules and the navigation structure connecting them
3. **Wireframing** — Low-fidelity structure for key flows (auth, task submission, attendance)
4. **Visual Design** — Designed a dark-mode-first UI system with a consistent component library (cards, tables, status badges, timelines, modals)
5. **Prototyping** — Built interactive flows in Figma covering full user journeys, including empty states, success states, and confirmation modals
6. **Documentation** — Compiled all 9 modules into a structured internship deliverable

---

## 🧩 Modules & Features

### 1️⃣ Onboarding & Authentication
Splash screen, landing page, login, signup, forgot password, OTP email
verification, and password reset — a complete, secure entry flow.

### 2️⃣ Dashboard
At-a-glance overview: attendance %, assigned/completed tasks, internship
progress ring, weekly attendance chart, recent activity feed, and a
visual progress timeline (Onboarding → Learning → Projects → Evaluation
→ Completion).

### 3️⃣ Tasks
Full task lifecycle: all tasks, in-progress, submitted, and completed
views with filtering, task detail pages with requirements and
attachments, a submission flow with file upload, and a status timeline
per task.

### 4️⃣ Attendance
Calendar-based attendance marking (Present / Late / Absent / Leave),
paginated attendance history, data export (Excel / PDF / CSV), and a
full leave request flow with guidelines and request tracking.

### 5️⃣ Learning Center
A built-in LMS: browsable resources, live training session
registration, categorized recorded material (Web Dev, Design, Project
Management, Data Science), and a certificates library with
downloadable, verifiable credentials.

### 6️⃣ Communication
Org-wide announcements, direct + group messaging, a discussion board
for peer knowledge-sharing, and a unified notification center.

### 7️⃣ Performance
Performance overview with score trends over time, mentor/peer feedback
with tagged strengths, earned badges/achievements, detailed score
breakdowns per task, and a full evaluation history.

### 8️⃣ Profile & Settings
Editable personal information, skill proficiency tracking, resume
upload with preview, a visual portfolio grid, social links, and full
account settings (appearance/theme, security, notifications, language).

### 9️⃣ Offboarding
A structured exit process: exit checklist with task-by-task tracking,
certificate request (with delivery method selection), an exit feedback
survey, and a final internship summary with a shareable completion
certificate.

---

## 🖼️ Screens

All **79 screens** are organized under [`/screens`](./screens), grouped
into the 9 modules above. Each folder contains its own `README.md`
listing every screen it holds, in order.

```
screens/
├── 01-onboarding-auth/     → Splash, landing, login, signup, OTP, password reset
├── 02-dashboard/           → Main dashboard
├── 03-tasks/               → Task list, details, submission, status
├── 04-attendance/          → Marking, history, export, leave requests
├── 05-learning-center/     → Resources, sessions, recordings, certificates
├── 06-communication/       → Announcements, messages, discussions, notifications
├── 07-performance/         → Scores, feedback, badges, evaluations
├── 08-profile-settings/    → Profile, skills, resume, portfolio, settings
└── 09-offboarding/         → Exit checklist, certificate request, feedback, completion
```

*(Open any folder above to view every screen in full resolution.)*

---

## 🎨 Design System

- **Theme:** Dark mode–first interface for reduced eye strain during extended use
- **Accent color:** Blue/purple gradient (`#4F7DF9` → `#8B5CF6` family) for primary actions and highlights
- **Status colors:** Green (completed/present), Yellow/Orange (pending/late), Red (rejected/absent), Blue/Purple (in progress/leave)
- **Typography:** Clean sans-serif hierarchy — bold headers, muted secondary text for metadata
- **Components:** Reusable cards, data tables with inline status badges, progress rings & bars, timelines, modals, and empty states
- **Consistency:** Persistent left sidebar navigation across all authenticated screens for predictable wayfinding

---

## 🛠️ Tools Used

- **Figma** — UI design, components, and prototyping
- **Figma Prototyping** — click-through flow simulation
---

## 💡 Key Learnings

- Designing for **multiple user states** (empty, loading, success, error) is as important as designing the "happy path" — over a third of these screens are confirmation, empty, or status states.
- A **consistent component system** (status badges, cards, tables) massively sped up designing 9 modules without visual drift.
- Structuring a large project into clear **modules** early made both design and documentation far more manageable.

---

## 👨‍👩‍👧‍👦 Team

This was a collaborative internship project built by:

- **Irfa Arshad**
- **Hafsa Saghir**
- **Amina Batool**
- **Alisha Muqadas**

---

## 📂 Project Files

- 📄 [Full Project PDF](./Internship_Project_1_Figma_Design.pdf) — original submission document
- 🖼️ [`/screens`](./screens) — all 79 exported screens, organized by module

---

## 📬 Contact

**Irfa Arshad**
🔗 [GitHub](https://github.com/IrfaArshad-Dev) · 💼 LinkedIn *(https://www.linkedin.com/in/irfa-arshad-833a77421/)*

---

<div align="center">
<sub>Built with care as part of an internship program • UI/UX case study</sub>
</div>
