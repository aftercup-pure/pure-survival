# Pure Survival

A distraction-free, high-contrast survival handbook designed for the **Minimal Phone** and other e-paper devices. Pure Survival packs practical, step-by-step field knowledge into a single offline HTML file, wrapped in a button-first interface with no scrolling menus, no animations and no clutter.

---

## 📱 Screenshot

<p align="center">
  <img src="https://i.postimg.cc/rsSW9nzB/IMG-0029.jpg" alt="Pure Survival" width="320">
</p>

---

## ✨ Key Features

### 📖 Handbook
Seventeen entries, each split into short pages so it stays readable on a slow e-ink refresh:

| # | Entry | # | Entry |
| :-: | :--- | :-: | :--- |
| 00 | Priorities | 09 | Knots |
| 01 | Water | 10 | Wildlife |
| 02 | Fire | 11 | Disasters |
| 03 | Shelter | 12 | Bug-out bag |
| 04 | Food | 13 | Mindset |
| 05 | Navigation | 14 | Trail Map |
| 06 | First Aid | 15 | Urban Shelter |
| 07 | Signaling | 16 | Notes |
| 08 | Weather | | |

* **Step-by-step instructions:** Numbered, boxed procedures you can follow under stress, not just encyclopedic text.
* **Warning boxes:** Critical dangers are always visible and marked with hazard stripes.
* **Urban Shelter:** A dedicated section for surviving in abandoned buildings instead of the wilderness.

### 🗺️ Trail Map
A plain fullscreen map with a Back button.
* Built on **Leaflet** with standard **OpenStreetMap** tiles.
* The official Hungarian marked-trail network (**MTSZ turistaút-nyilvántartás**) is overlaid on top.
* Asks for location access and shows where you are, with a one-tap re-center button.
* The map libraries are loaded only when you open the map, so the rest of the app never touches the network.

### 📝 Notes
Simple plain-text notes saved in `localStorage`. Nothing leaves your device.

### 🖤 Designed for e-ink
* Pure black and white, no grays for essential content, no animations or transitions.
* Large tap targets and a tile-based home screen that scales to fill the screen exactly.
* One button cycles through three text sizes (`A` / `A+` / `A++`).
* Fixed header: the menu and the page viewer live in one compact bar.
* Every icon is an inline SVG, so there are no icon fonts and no external requests.

---

## ⌨️ Navigation

Everything works with buttons, and physical keys work too:

| Key | Action |
| :--- | :--- |
| <kbd>→</kbd> / <kbd>PageDown</kbd> | Next page |
| <kbd>←</kbd> / <kbd>PageUp</kbd> | Previous page |
| <kbd>Esc</kbd> | Close the info panel |

* **Home:** Tap the title to return to the tile menu from anywhere.
* **Topic menu:** A dropdown in the header jumps straight to any entry.
* **Search:** Filters all entries by text.
* **Deep links:** Every entry has its own address (for example `#s06` opens First Aid).

---

## 🚀 Technical details

* **Version:** `v0.1.1`
* **Platform:** Optimized for the Minimal Phone MP01 (works in any modern browser)
* **Stack:** One self-contained HTML file in vanilla HTML/CSS/JS. No build step, no frameworks.
* **Storage:** Notes in `LocalStorage`; no account, no cloud, no tracking.
* **Offline:** The whole handbook works offline. Only the Trail Map needs a connection.
* **Location:** Browsers only allow geolocation on `https://` or `localhost`. If you wrap the app in a WebView, grant the location permission at app level too.

---

## 📥 Installation

1. Download `survival-handbook.html`.
2. Open it in any browser, or wrap it in an Android WebView.
3. *(Optional)* Add it to your home screen for one-tap access.

---

## 🔗 Links

* **GitHub:** https://github.com/aftercup-pure/

*Made for Minimal Phone MP01.*
