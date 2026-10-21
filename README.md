# Bunkometer — High-Seas 3D Attendance Tracker & Bunk Navigator ⚓🏴‍☠️

## Overview
**Bunkometer High-Seas Edition (v4.0)** is a modern, interactive attendance tracking dashboard set in an original **high-seas pirate adventure / maritime fantasy universe**.

Designed for college and university students who want to navigate their attendance voyage with precision and zero mental math.

---

## 🌟 Core Features & Highlights

### 1. 🗓️ Interactive Calendar & Future Bunk Simulator *(New in v4.1)*
* **Touch-to-Preview Future Dates**: Tap on any future calendar date to instantly view its scheduled timetable lectures and simulate the exact impact if you take leave on that day.
* **Instant Future Mathematical Projection**:
  * Projected attendance percentage drop (e.g. `81.8%` $\to$ `78.2%`).
  * Safety verdict: 🟢 Safe, 🟡 Caution, or 🔴 Detention Risk.
  * Remaining safe bunk margin after taking the leave.
* **Multi-Day Planned Leaves Bank**: Bookmark upcoming dates as planned leaves (festivals, events, long weekends); view cumulative projected attendance across your entire semester.
* **Past & Today Attendance Logging**: Color-coded date dots matching the standard attendance scheme:
  * 🟢 **Full Day**: Attended all scheduled lectures.
  * 🟡 **Partial**: Attended some, missed some.
  * 🔴 **Absent / Bunked**: Missed the full day.
  * ⚪ **Holiday**: Scheduled rest day or college holiday.
* **Refined Monthly Card**: Modern calendar layout with month navigation (`<` and `>`), "Today" quick jump, and active day highlight.

### 2. 📅 Weekly Timetable & "Today's Voyage" 1-Tap Logger
* **Today's Classes at a Glance**: Automatically detects today's day of the week and displays scheduled lectures with 1-tap **`+ Attend ⚓`**, **`+ Bunk 🏴‍☠️`**, and **`↩ Undo`** action buttons.
* **Whole-Day Fast Actions**: Log all lectures for the day as attended (`⚡ Mark Whole Day Attended`) or missed with a single tap.
* **Day Switcher**: Seamlessly toggle between Monday through Saturday to review or log past or future days directly from the overview.
* **Timetable Editor**: Interactive manager for class periods with time slots, course selection dropdowns synced to your fleet, and auto-populate presets.

### 2. 🗺️ Timetable-Grounded Bunk Feasibility Radar *(New in v4.0)*
* **Real-World "Can I Bunk Today / Friday?"**: Replaces simple averages with an exact course-by-course simulation.
* Checks every course scheduled on that day and verifies if skipping that day will breach criteria for any individual course.
* **Visual Feasibility Badges**:
  * 🟢 **Safe Day**: All scheduled courses retain positive safety margins above target.
  * 🟡 **Caution Day**: 1 or more courses will enter borderline rough seas.
  * 🔴 **Cannot Bunk**: Detention risk — skipping drops a course below target attendance!
  * 🏝️ **Port Rest Day**: Scheduled free day / weekend.

### 3. 🔄 Instant Fleet Overview Sync *(New in v4.0)*
* Keep your main Astrolabe needle and Captain's Banner synchronized with the sum of all individual courses in your Fleet Logbook with 1 click.

### 4. 🌊 Immersive 3D High-Seas Environment (100% Stable UI)
* **Zero UI Shaking**: All 3D movement, ocean waves, clouds, rotating antique astrolabe, and the distant sailing pirate galleon exist **strictly in the background environment surrounding the UI**.
* **Rock-Solid Interface**: The cards, inputs, buttons, and tables remain completely stable, crisp, and effortless to click and read on both mobile and desktop.

### 5. 🗺️ Bunk Navigator ("How Many Days Can I Bunk?")
* Dedicated calculator that translates allowable class skips into **Full Calendar Days Off**.
* Enter your **Classes Conducted Per Day** (e.g. 4 or 5 lectures).
* Calculates:
  * **Target Attendance** (e.g. 75%)
  * **Current Attendance Rate**
  * **Classes You Can Still Miss**
  * **Full Days You Can Bunk**
  * **Remaining Extra Single Classes** (shown separately without upward rounding).

### 6. ⚓ Captain's Overview & Nautical Astrolabe Gauge
* Synchronized 4-input cluster: **Total Held**, **Attended**, **Missed**, and **Target %** auto-harmonize with each other.
* Brass astrolabe gauge with laser pointer and 3 distinct navigational states:
  * 🟢 **Calm Waters (Safe)**: Emerald sea green & gold glow.
  * 🟡 **Rough Seas (Warning)**: Lantern amber glow.
  * 🔴 **Kraken's Reach (Below Target)**: Crimson alert with exact consecutive classes needed to recover.

### 7. 🔮 Voyage What-If Simulator
* **"If I miss $X$ more classes"** live slider: Project your future percentage and margin instantly.
* **Target Comparison Matrix**: Instant side-by-side view of allowable misses for **75%**, **80%**, **85%**, and **90%** attendance criteria.

### 8. 📜 Fleet Logbook (Subject-Wise Tracking)
* Track individual courses and practicals.
* 1-tap quick action buttons: **`+ Attend`**, **`+ Bunk`**, and **`↩ Undo`**.
* Per-subject target threshold override (e.g., 80% for Labs, 75% for Theory).
* Total fleet summary and risk indicators.

### 9. 🏴‍☠️ Pirate's Vault (Backup & Portability)
* Export & Restore JSON Ship Logs (including your complete weekly timetable).
* Download formatted CSV voyage sheets.
* Copy instant text dispatch reports for WhatsApp/Discord.
* 100% private, client-side, zero tracking, and offline PWA ready.

---

## 🛠️ Tech Stack
- **HTML5 & Vanilla JavaScript** (Zero frameworks, lightning fast performance)
- **HTML5 Canvas** (Lightweight multi-harmonic ocean waves & animated sailing galleon)
- **Web Audio API** (Nautical bell and chime synthesis)
- **CSS3 Glassmorphism** (Frosted dark obsidian & antique brass borders)
- **Google Fonts**: Cinzel, Rajdhani, JetBrains Mono, Inter.

---

## 🚀 Live Demo
- **GitHub Pages**: [https://nikhilsingh187.github.io/Bunkometer/](https://nikhilsingh187.github.io/Bunkometer/)
- **Netlify**: [https://sweet-bubblegum-1c80ee.netlify.app](https://sweet-bubblegum-1c80ee.netlify.app)
