# 🚀 GATE CSE 2027 Master Tracker

<div align="center">
  <img src="assets/History.png" width="32%" alt="Dashboard View">
  <img src="assets/Book_of_Mistakes.png" width="32%" alt="Test History View">
  <img src="assets/Command.png" width="32%" alt="Book of Mistakes View">
</div>

<br>

A zero-friction, fully local web application designed for GATE Computer Science Engineering (CSE) aspirants. This tool moves beyond simple spreadsheets by integrating automated test analysis, dynamic Spaced Repetition System (SRS) alerts, and an offline "Book of Mistakes" to surgically target weak areas.

## ✨ Core Features

*   **📊 Command Center & Momentum:** Tracks your 7-day study streak, displays a live GATE 2027 countdown, and generates "Daily Tactical Missions" based on your most overdue topics.
*   **🧠 Spaced Repetition System (SRS):** Automatically categorizes topics by difficulty (Hard=3 days, Medium=7 days, Easy=15 days) and alerts you exactly when a concept is about to be forgotten.
*   **📓 The Book of Mistakes (IndexedDB):** Log incorrect and skipped questions alongside their "Root Cause." Features dual file uploads allowing you to attach screenshots/PDFs of both the Question and the Solution locally.
*   **🔬 Micro-Topic Analytics:** Hardcoded with 80+ official GATE CSE topics. Calculates Net Score, Accuracy, and Identifies your exact vulnerability (e.g., "Silly Mistakes" vs "Conceptual Gaps").
*   **⚙️ Auto-Scoring Engine:** Automatically applies the official GATE negative marking logic (-0.33 for 1M, -0.66 for 2M MCQs, 0 penalty for MSQ/NAT).
*   **🛡️ 100% Privacy & Data Ownership:** Completely serverless. All data is securely stored in your browser using `localStorage` (text data) and `IndexedDB` (files). Includes a robust JSON Export/Import feature for manual backups.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
*   **Visualization:** [Chart.js](https://www.chartjs.org/) (Loaded via CDN)
*   **Database (Text/Metrics):** Browser `localStorage`
*   **Database (Files/Images/PDFs):** Browser `IndexedDB` (bypasses the 5MB local storage limit)

## 🚀 How to Run Locally

Because this is a serverless, client-side application, installation is instantaneous.

1. Clone the repository:
```bash
   git clone [https://github.com/Sriramsahoo2004/gate-cse-tracker.git](https://github.com/Sriramsahoo2004/gate-cse-tracker.git)

2. Open the folder and double-click index.html (or whatever you named the file) to open it in any modern browser (Chrome, Edge, Brave, Firefox).

3. Start logging your mock tests!

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! If you want to fork this and adapt it for GATE EE, ME, or ECE, simply update the CSE_SYLLABUS JSON object inside the <script> tag.
