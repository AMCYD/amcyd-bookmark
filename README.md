## Cybersecurity Browser Bookmarks
Open website here:
 https://amcyd.github.io/amcyd-bookmark/


 This project isn’t just a static link list—it’s an **interactive browser startpage and bookmark dashboard** (Bookmarks VantGate) built as a client-side web application. It features real-time search, multi-engine routing, custom themes, and JSON/HTML import-export tools.

The `README.md` below matches a focused dashboard project rather than an overblown directory, highlighting its live demo, feature set, keyboard shortcuts, and simple deployment steps.

---

```markdown
# 🔖 Bookmarks VantGate

A sleek, lightweight, client-side startpage and bookmark manager tailored for cybersecurity analysts, penetration testers, and tech tinkerers.

[![Live Demo](https://img.shields.io/badge/Demo-Live%20Page-brightgreen?style=flat-square)](https://amcyd.github.io/amcyd-bookmark/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## ⚡ Quick Look

**Bookmarks VantGate** turns your browser's new tab page into a centralized dashboard for offensive, defensive, and IT tools without storing your data on third-party servers.

- 🌐 **Live App:** [amcyd.github.io/amcyd-bookmark](https://amcyd.github.io/amcyd-bookmark/)
- 💻 **Zero Backend:** Runs entirely in your browser using `localStorage`.

---

## ✨ Features

- **Multi-Engine Quick Search:** Instant query switching across Google, Bing, DuckDuckGo, Brave, Startpage, and Yandex.
- **Interactive Command Palette:** Instant access to links via <kbd>Ctrl</kbd> + <kbd>K</kbd>.
- **Fast Bookmark Addition:** Add links with automatic favicon, title, and metadata fetching via <kbd>Ctrl</kbd> + <kbd>B</kbd>.
- **Deep Customization:**
  - Presets & custom linear gradients.
  - Background blurs, card opacities, and corner radiuses.
  - Accent colors and custom typography (Inter, Monospace, System Default).
  - List and grid view toggles per category.
- **Portable & Private:** Export and import your data anytime via standard JSON or browser-compatible HTML bookmark formats.

---

## ⌨️ Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Ctrl</kbd> + <kbd>K</kbd> / <kbd>Cmd</kbd> + <kbd>K</kbd> | Open Command Palette / Quick Search |
| <kbd>Ctrl</kbd> + <kbd>B</kbd> / <kbd>Cmd</kbd> + <kbd>B</kbd> | Open "Add Bookmark" modal |
| <kbd>Enter</kbd> | Open selected search result |
| <kbd>Tab</kbd> | Copy selected URL to clipboard |
| <kbd>Esc</kbd> | Close active modal or search palette |

---

## 🚀 Getting Started

No build tools, Node modules, or servers required.

### Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/amcyd/amcyd-bookmark.git](https://github.com/amcyd/amcyd-bookmark.git)
   cd amcyd-bookmark

```

2. **Open in browser:**
Double-click `index.html` or serve via Python:
```bash
python3 -m http.server 8080

```


Open `http://localhost:8080` in your browser.

### Use as Your Browser Startpage

1. Open your browser settings.
2. Under **On startup** or **Home page / New windows**, select **Open a specific page**.
3. Paste:
```text
[https://amcyd.github.io/amcyd-bookmark/](https://amcyd.github.io/amcyd-bookmark/)

```



---

## 💾 Backups & Sync

All bookmarks, tags, categories, and theme settings live in your browser's local cache.

1. Click **⚙️ Settings** (bottom corner).
2. Go to **Data Management**.
3. Select **Export JSON** to backup your setup, or **Import** to load bookmarks on another device or private window.

---

## 🛠️ Built With

* Vanilla HTML5, CSS3, and JavaScript
* Native Browser Web APIs (`localStorage`, `fetch`)
* Hosted on GitHub Pages

---

## 📄 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

```

<FollowUp label="Want to include a pre-populated default bookmarks JSON file for first-time visitors?" query="How can I add default cybersecurity categories and bookmarks to localStorage on first launch for Bookmarks VantGate?"/>

```
