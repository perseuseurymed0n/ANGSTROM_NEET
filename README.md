# ⚛️ ANGSTROM — NEET Mistake Journal

> **No account. No server. No internet required after loading. Everything stays on your device.**
NOTE: Only Browsers that Support File System Access API. E.g. Chrome, Edge, Brave etc. Brave users need to turn it on manually as it is turned off default.
---
1. Easiest Way: Use the Deployed GitHub Page
Just click this link and start using the app instantly:
 Open Angstrom NEET Mistake Journal
Create a DEDICATED Folder of your choice and LINK the html file with it (Go to settings and click it)
<img width="1000" height="935" alt="image" src="https://github.com/user-attachments/assets/692d4d7b-30df-4c11-a96a-bd701366e8b3" />
(Replace with your actual GitHub Pages link after enabling it)
No installation. No download. Works directly in your browser.

**IMPORTANT**: Make sure to link to a device folder for the BEST efficiency. Otherwise, the applet DEFAULTS to using JSON for images which is storage heavy!

2. Run Completely Offline (Download HTML File)
If you want to use the app without internet or prefer to keep everything local:

Go to the GitHub repository
Click on the file anatom_fixed.html (or angstrom.html)
Click the "Download raw file" button (or right-click → Save As)
Save the file anywhere on your device (e.g., Desktop or NEET folder)
Double-click the downloaded .html file
Create a DEDICATED Folder of your choice and LINK the html file with it 
<img width="1000" height="935" alt="image" src="https://github.com/user-attachments/assets/692d4d7b-30df-4c11-a96a-bd701366e8b3" />

It will open in your default browser and work 100% offline.
Tip: Create a shortcut on your desktop for quick access.
## Features

###  Question Logging
- Add questions with full **rich text editing** — bold, italic, headings, lists, tables, highlights, and more
- Native **LaTeX / MathJax support** — write `$F = ma$` and see it rendered instantly in a live preview
- Attach **diagrams or screenshots** via drag-and-drop or file picker
- Add **A/B/C/D answer options** with correct answer marking
- Write a detailed **solution and reflection** with the same rich text editor
- Tag each question with **subject** (Physics / Chemistry / Biology), **chapter**, **difficulty** (1–5 stars), **mistake type**, and **test source**

### Spaced Repetition Review
- Built-in **SM-2-style spaced repetition** schedules reviews at 1 → 3 → 7 → 15 → 30 day intervals
- **Review Queue** on the dashboard shows exactly what's due today
- Mark questions as remembered or needing more practice to update the schedule

###  Analytics
- Visual breakdown of mistakes by **subject** (pie chart)
- **Weakest chapters** bar chart — see at a glance where you need the most work
- Track **most common mistake type** and **weekly activity**

###  Search & Filter
- Full-text search across all logged questions
- Filter by subject, chapter, mistake type, difficulty, coaching institute, and test type

###  Export Question as Image
- Export any question as a **styled PNG image** (3 themes: Simple, Card, Dark)
- Options to include/exclude answer options, solution, tags, difficulty, watermark
- Perfect for sharing to study groups or WhatsApp

###  PDF Export
- Export your entire question log as a **formatted printable PDF**

###  Flexible Storage
- **Default:** All data saved in browser `localStorage` — zero setup needed
- **Optional:** Connect a **local device folder** via the File System Access API for larger storage with real files you can back up yourself
- **JSON import/export** for manual backups and restoring data

###  Appearance
- Dark academic theme (default) and light parchment theme
- Fully responsive layout

---

## ⚠️ Important — Read Before Using

> This app stores all your data **locally on your device only**. There is no server, no cloud sync, and no account system.


 **Data loss**  Clearing browser cache or resetting your device will permanently erase all data. There is no recovery. 
 **Back up regularly**  Go to **Settings → Export JSON** and save the file somewhere safe (Google Drive, USB, email). 
 **Safer option**  Connect a local folder in **Settings → Device Storage** — your data is saved as real files independent of the browser. 
 **Privacy**  Each person who opens this app gets their own completely isolated journal. Data is never shared between users. 
 **Offline**  The app works fully offline after the initial page load. 

---

##  Getting Started

### Use the hosted version
If this repo has GitHub Pages enabled, just open the link and start using it — no installation needed.

### Run locally
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
# Open index.html in any modern browser
open anatom_fixed.html
```

No build step, no dependencies, no `npm install`. It's a single HTML file.



---

##  Tech Stack


 [MathJax 3.2](https://www.mathjax.org/)  LaTeX / TeX math rendering 
 [Chart.js 4.4](https://www.chartjs.org/)  Analytics charts 
 [html2canvas 1.4](https://html2canvas.hertzen.com/)  Question PNG export 
 [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Instrument Sans](https://fonts.google.com/specimen/Instrument+Sans) 
 File System Access API | Optional device folder storage 
 IndexedDB | Persisting folder handle across sessions 
 localStorage  Default data storage 

Zero frameworks. Zero build tools. Pure HTML + CSS + JS in a single file.

---

##  Project Structure

```
/
└── anatom_fixed.html   # The entire app — one self-contained file
└── README.md
```

---

##  Privacy

- No analytics, no tracking, no ads, no external API calls (except loading fonts and MathJax from CDN on first load)
- Your questions, solutions, and images never leave your device
- The developer cannot access your data — it physically doesn't exist on any server

---



  # NOTE: This project is FULLY AI generated. I do not claim to have coded any part in this.

