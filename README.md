# 📖 StudyWatch — Student Reading Time Tracker

A lightweight, installable web app for students to track how long they spend on each page or section while studying. No accounts, no ads, no internet required after install — everything saves locally on your device.

---

## What It Does

StudyWatch helps you stay aware of your reading pace so you can study smarter. You start the timer when you begin a page, save it when you finish, and over time the app builds a picture of how fast you read and how much time is left in your session.

Specifically it:

- Times each page or section individually with millisecond precision
- Saves each entry to a local history grouped by date
- Compares each new entry to the previous one (faster / slower / baseline)
- Estimates what time you'll finish based on your average pace and pages remaining
- Tracks your best time, average time, total time, and daily page count
- Shows a bar chart of your last 10 pages so you can spot slow patches
- Keeps a daily study streak counter to keep you motivated
- Supports multiple books or subjects in separate trackers
- Lets you set a daily page goal with a live progress bar
- Records lap splits mid-page if you want finer breakdowns

---

## How to Use

### Basic Flow

1. Open the app and pick or create a book/subject from the dropdown at the top
2. Type the page number or section name in the input field (e.g. `Page 42` or `Chapter 3 Intro`)
3. Tap **▶ Start** when you begin reading
4. Tap **⏸ Pause** if you need a break — the timer holds
5. Tap **✓ Save** when you finish the page — it logs the time and auto-increments the page number for you
6. Repeat for each page

### Estimating Finish Time

Enter how many pages you have left in the **"pages left"** field at the bottom of the timer. Once you have at least one saved entry, the app will calculate your average pace and tell you what time you'll finish and how long it will take.

### Lap Splits

Tap the **⏱ lap button** (clock icon) during a session to record a split without saving the full entry. Useful for timing individual paragraphs or sub-sections within a page.

### Multiple Books

Tap **+ Book** next to the dropdown to create a separate tracker for a new subject. Each book has its own history, goal, and stats — switching books is instant.

### Daily Goals

When creating a book, set a daily page goal. A progress bar appears below the header showing how many pages you've done today vs. your target. You can also set a default goal in Settings (gear icon).

### Analytics

Tap the **Analytics** tab or the chart icon in the top right to see your study streak, overall stats (total pages, best page time, average), and a bar chart of your recent sessions.

### Deleting Entries

Hover over (or long-press on mobile) any history card to reveal a small ✕ button that deletes just that entry.

---

## Installing as an App (PWA)

StudyWatch is a Progressive Web App — you can install it on your phone or desktop and use it offline like a native app.

**Android (Chrome)**
Open the site → tap the three-dot menu → tap "Add to Home Screen"

**iPhone / iPad (Safari)**
Open the site → tap the Share button → tap "Add to Home Screen"

**Desktop (Chrome / Edge)**
Look for the install icon in the address bar → click "Install"

Once installed, the app works fully offline. All your data is stored on your device and never sent anywhere.

---

## Data & Privacy

All data is stored in your browser's `localStorage`. Nothing is sent to any server. Clearing your browser data or uninstalling the app will erase your history, so export important records manually if needed.

---

## Credits

Built with HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no dependencies.

**AI contribution:** Claude AI (Anthropic) — ~70% — architecture, logic, UI design, and PWA setup

**Owner contribution:** ~30% — concept, original prototype, feature direction, and refinement

---

*StudyWatch — track the page, own the pace.*
