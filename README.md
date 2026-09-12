# Bunkometer PRO — Attendance Safety & Bunk Simulator 🎓

## Overview
Every college student knows the 75% attendance anxiety — the constant mental math of:
> *“How many classes can I actually skip without getting detained?”*  
> *“If I miss next Monday, where does my percentage land?”*  
> *“How many classes in a row do I need to attend to recover?”*

**Bunkometer PRO** turns that mental chaos into an interactive instrument cluster. Built for students who calculate risk before they calculate marks.

---

## What's New in v2.0 ✨

### 1. ⚡ 1-Tap Quick Attendance Logger
- Don't waste time typing numbers every day.
- Tap **`+ Attend`** or **`+ Bunk`** on any subject card to instantly record your class with 1 click.
- Made a mistake? Tap **`Undo`** to immediately revert your last action.

### 2. 🔮 Interactive "What-If" Simulator
- Test future scenarios before skipping!
- Project attendance for any individual subject or across all subjects combined.
- Steppers for:
  - *“Attend next $N$ classes”*
  - *“Bunk next $N$ classes”*
- Live delta badge showing percentage gain/loss and resulting safe margin.
- **“Apply to Subject”** button to commit simulation directly to your real records if desired.

### 3. 📱 Responsive Cards & Table Layout
- **Cards View**: Optimized for mobile phones with visual progress bars, status badges, and quick-action toolbars.
- **Table View**: Dense spreadsheet style for desktop power users.
- Switch between views anytime with one click.

### 4. 🎯 Per-Subject Custom Targets
- Customize attendance criteria per subject (e.g. 80% for Labs, 75% for Theory, 85% for Honors).
- Default to global threshold or override on each subject card.

### 5. 🏦 Bunk Bank & Analytics Vault
- **Bunk Bank**: Calculates total safe skips remaining across all passing subjects combined.
- **Attendance Debt**: Sums up consecutive classes needed across all deficit subjects.
- **High-Risk Alerts**: Highlights subjects currently in caution or detention zones.

### 6. 💾 Backup & Data Portability
- **Export Backup (`.json`)**: Download your full attendance record.
- **Restore Backup (`.json`)**: Upload and restore anytime on any browser or phone.
- **Download CSV Sheet**: Generate a clean spreadsheet with attendance stats for submissions.
- **Copy Summary**: Formats a clean clipboard snippet for sharing.

### 7. 🔊 Web Audio Feedback & PWA Ready
- Subtle, satisfying audio synthesizer chimes when marking attendance (toggleable anytime).
- **PWA Ready**: Install Bunkometer as an app on your Android / iOS home screen with offline support.

---

## Tech Stack 🛠️
- **HTML5 & CSS3** (Custom cyberpunk/instrument cluster dark theme, responsive grid/flexbox)
- **Vanilla JavaScript** (Zero frameworks, zero dependencies, lightning fast)
- **Web Audio API** (Pure mathematical synthesized sound chimes)
- **Service Worker & Web App Manifest** (Offline PWA support)
- **LocalStorage Engine** (100% private, client-side, zero tracking)

---

## Quick Start 🚀
Simply open `index.html` in any modern web browser:
```bash
# Clone the repository
git clone https://github.com/your-username/bunkometer.git
cd bunkometer

# Open in browser
start index.html  # On Windows
# or open index.html on macOS / Linux
```

---

## Privacy 🔒
Everything lives and runs exclusively inside **your browser**. No cookies, no external servers, no tracking, and zero data collection.
