# Pure Calendar

A distraction-free, high-contrast calendar application specifically designed for the **Minimal Phone** and other e-paper devices. Aftercup Calendar combines essential productivity tools with a unique integration of the Aftercup coffee blog, wrapped in a QWERTY-optimized interface.

---

## 📱 Screenshots

| | |
| :---: | :---: |
| ![Home Screen](https://i.postimg.cc/QCm57G69/Screenshot-20260516-185705.png) | ![New Entry](https://i.postimg.cc/sxs71DJ1/Screenshot-20260516-185715.png) |
| ![Briefing](https://i.postimg.cc/0jnmSRtm/Screenshot-20260516-185738.png) | ![Menu](https://i.postimg.cc/Wz8rZL9d/Screenshot-20260516-185727.png) |
| ![Account](https://i.postimg.cc/zv8K3Xkv/Screenshot-20260516-185803.png) | ![Minimal month popup](https://i.postimg.cc/Y0RgFKXY/Screenshot-20260516-185745.png) |
| ![Search](https://i.postimg.cc/sxs71DJD/Screenshot-20260516-185825.png) | ![Upcoming](https://i.postimg.cc/L52Lh6VX/Screenshot-20260516-185843.png) |
| ![Shift planner](https://i.postimg.cc/prC8jb0j/Screenshot-20260516-190007.png) | ![Instant jump](https://i.postimg.cc/hvsxmWC4/Screenshot-20260516-185929.png) |

---

## ✨ Key Features

### 📅 Core functionality
The app serves as a central hub for your daily life, supporting multiple entry types:
* **Events:** Standard time-based appointments with physical or virtual location support.
* **Tasks:** To-do items with interactive checkboxes and completion states.
* **Notes:** Rich text entries supporting **Bold**, *Italic*, <u>Underline</u>, and ~~Strikethrough~~. Notes feature a smart "show more" toggle to keep the daily view clean.
* **Routines:** A powerful recurring engine that allows for entries to repeat every $X$ days, weeks, or months with optional end dates.

### ☕ Aftercup integration
Built-in support for the (hungarian) Aftercup coffee blog (can be toggled in/out in settings):
* **Blog Entries:** View the latest coffee culture posts directly in your timeline.
* **Aftercup Brief:** A dedicated daily summary popup combining your scheduled agenda, geolocation-based weather reports, and blog updates.

### 💭 Dream journal
A private space to record your dreams. Associate entries with specific years to track your subconscious journey over time.

### 👗 Background patterns
Decorate your calendar with beautiful new botanical backgrounds! Alongside our classic Horse theme, you can now customize your daily view with elegant Monstera and Tulip patterns. These responsive designs bring a fresh, natural vibe to your screen and look fantastic in both light and dark modes.

---

## ⌨️ QWERTY keyboard support

Designed for devices with physical keyboards. Control the entire app without touching the screen:

| Key | Action |
| :--- | :--- |
| <kbd>T</kbd> / <kbd>Y</kbd> / <kbd>N</kbd> | Jump to **T**omorrow, **Y**esterday, or **N**ow (Today) |
| <kbd>C</kbd> | Open **C**alendar date picker |
| <kbd>H</kbd> | Access the S**h**ift Planner |
| <kbd>P</kbd> / <kbd>D</kbd> / <kbd>U</kbd> / <kbd>I</kbd> | Quick access: **P**ocket, **D**reams, **U**pcoming, and H**i**story |
| <kbd>A</kbd> / <kbd>S</kbd> | Open **A**ftercup brief or Account **S**ettings |
| <kbd>F</kbd> | Search between added entries |
| <kbd>↵</kbd> | Add a new enrty |
| <kbd>⌫</kbd> | Close active popups or return to homescreen |

> **Quick Jump to Day:** Simply type a number (<kbd>1</kbd>-<kbd>3</kbd><kbd>1</kbd>) on the home screen. A mini popup appears for two-digit entry. After 2.5 seconds, the calendar automatically jumps to that day.

---

## 🛠️ Professional tools

* **Symbol-based Shift Planner:** Track work cycles using high-visibility icons for morning, afternoon, night, resting, holiday, and sick pay.
* **Print week overview:** Generate a clean, printer-friendly summary of your current week.
* **Cloud sync & backup:** Securely backup to the cloud (Aftercup Account) or perform manual local exports/restores via `.json` files for total data sovereignty.
* **Google Calnedar support:** Save your calendar entries to Google Calendar or import them from there.

---

## 🚀 Technical details

* **Version:** `v1.0.1` (MP01 build)
* **Platform:** Optimized for Android/Web (Minimal Phone hardware)
* **Storage:** `LocalStorage` persistence with optional cloud sync via Google Apps Script API.
* **Notifications:** Service Worker-based daily summary with Weather API integration. **Notifications are currently unstable due to web environment limitations!**

---

## 📥 Installation

1. Download the latest **APK** from the release badge below.
2. Install on your **Minimal Phone**.
3. *(Optional)* Log in to enable automatic cloud synchronization across devices.

[![Normal version on Google Play](https://img.shields.io/badge/Google_Play-normal_verion-000000?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.aftercup.calendar&hl=en)
