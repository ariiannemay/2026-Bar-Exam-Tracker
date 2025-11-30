# ⚖️ 2026 BAR EXAM REVIEW TRACKER

**App Link:** [2026bar-reviewtracker.vercel.app](2026bar-reviewtracker.vercel.app/)

-----

## 💡 About This Project

I built this web application for myself—a fellow 4th-year law student—to meticulously track my study progress for the 2026 Bar Exam. I customized and expanded upon a popular methodology (like a complex planning sheet) and turned it into a dynamic, personal app using HTML, JavaScript, and modern CSS.

This tracker is designed to be my central hub for scheduling, organization, and visual feedback as I prepare for the bar.

-----

## ✨ Key Features (My Personal Study Flow)

### 1\. The Command Center: Deadlines and Progress at a Glance

The main dashboard provides instant, essential information:

  * **Custom Countdown Timers:** Tracks the exact time remaining until each of the three Bar Exam days. I can easily adjust these dates if the Supreme Court moves the schedule.
  * **Overall Progress Meter:** A live pie chart visually shows my **"DONE"** vs. **"TO-READ"** status across the entire syllabus. A topic is only "DONE" if I've reviewed it thoroughly (the **3-of-5 Rule**).
  * **Schedule Summary:** A table breaks down the schedule, displaying the exact **weight** of each subject (e.g., Remedial Law is 25%) and showing a mini progress bar for each one.

| 🖥️ Tracker Header Overview |
| :---: |
| \<img src="[https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%20Bar%20Review%20Tracker%20-%20Preview/2026%20Bar%20Review%20Tracker%20-%20Preview%201%20-%20Header.png](https://www.google.com/search?q=https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview%25201%2520-%2520Header.png)" alt="Preview showing the header and overall progress meters" width="800"/\> |

### 2\. Subject Breakdown: Multi-Dimensional Tracking

The tracker is organized into six expandable panels (one for each Bar subject).

  * **Tracking Mechanism:** For each core topic within the syllabus, I assigned **five individual checklist boxes** representing different study materials: **Codal, Books, Reviewer, Bar QAs, and Cases.**
  * **The 3-of-5 Rule:** This is the core logic: a topic is only counted as **"DONE"** if I check at least 3 out of the 5 review method boxes, enforcing comprehensive study.
  * **Visual Checkmarks:** The checkboxes are color-coded (e.g., Codal is violet, Bar QAs is green) to quickly identify the material type I've finished.

| 📋 Example: Remedial Law (REM) Tracker |
| :---: |
| \<img src="[https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%20Bar%20Review%20Tracker%20-%20Preview/2026%20Bar%20Review%20Tracker%20-%20Preview%203%20-%20REM.png](https://www.google.com/search?q=https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview%25203%2520-%2520REM.png)" alt="Preview showing the detailed checklist for Remedial Law" width="800"/\> |

### 3\. Integrated Planning & Notes

  * **Interactive Calendar:** I can click any day in the calendar to quickly **schedule a specific subject topic or a personal event**.
  * **Digital Notepad:** The permanent notepad sidebar is where I jot down quick thoughts, temporary checklists, or urgent deadlines. It features **Undo, Redo, Clear, and Copy** functions, and saves automatically as I type.

| 📅 Calendar and Notepad Preview |
| :---: |
| \<img src="[https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%20Bar%20Review%20Tracker%20-%20Preview/2026%20Bar%20Review%20Tracker%20-%20Preview%202%20-%20Calendar.png](https://www.google.com/search?q=https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview%25202%2520-%2520Calendar.png)" alt="Preview showing the monthly calendar view and notepad" width="800"/\> |

-----

## 💾 Data & Technical Notes

### Data Portability

  * All my progress, notes, and custom dates are saved **locally in my browser** (Local Storage).
  * I can easily back up and restore my progress using the **Export All Data** and **Import Existing Data** buttons, which generate and read a local `.json` file.

### Important: Browser Dependency

  * This application was primarily built and tested for **Google Chrome**. Full compatibility and performance on other browsers (Safari, Firefox, etc.) cannot be guaranteed.
  * The tracker requires an **active internet connection** to load its core libraries (Tailwind CSS, jQuery, FullCalendar).

| ⚙️ Footer and Data Management Preview |
| :---: |
| \<img src="[https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%20Bar%20Review%20Tracker%20-%20Preview/2026%20Bar%20Review%20Tracker%20-%20Preview%209%20-%20FOOTER.png](https://www.google.com/search?q=https://raw.githubusercontent.com/ariiannemay/2026-Bar-Exam-Tracker/main/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview/2026%2520Bar%2520Review%2520Tracker%2520-%2520Preview%25209%2520-%2520FOOTER.png)" alt="Preview showing the data management buttons and footer quote" width="800"/\> |
