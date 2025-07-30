<div align="center">
  <img src=".github/assets/claverpage-banner.png" alt="Claverpage Banner"/>
</div>

# Claverpage ✨

<div align="center">

[![License](https://img.shields.io/badge/License-Custom-blue.svg)](LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/siddhantdg/Claverpage.svg)](https://github.com/siddhantdg/Claverpage/commits/main)
[![Repo size](https://img.shields.io/github/repo-size/siddhantdg/Claverpage.svg)](https://github.com/siddhantdg/Claverpage)

</div>

Welcome to Claverpage! This isn't just a static page; it's a fully-featured, productivity-focused browser homepage designed for speed, style, and customization. It serves as a personal dashboard to launch you into your web activities.

---

## 🚀 Live Demos: Choose Your Experience

Claverpage is available in several versions, each tailored for a specific need. The **Main Experience** is recommended for most users.

| Version               | Description                                                                                             | Live Link                                                                    |
| --------------------- | ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| 🚀 **Main Experience**    | The complete version with all features and animations. **This is the recommended version for personal use.**      | **[Open `index.html`](https://siddhantdg.github.io/Claverpage/)**          |
| 🏢 **Claver Edition**     | Identical to the Main Experience, but with the "Siddhant" branding replaced by the neutral "Claver".  | **[Open `claver.html`](https://siddhantdg.github.io/Claverpage/claver.html)** |
| ⚡ **Lite Version**        | A lightweight build with some blur animations disabled for maximum performance on older devices.      | **[Open `lite.html`](https://siddhantdg.github.io/Claverpage/lite.html)**      |
| 🖥️ **Wide-Screen Mode** | A compatibility version designed for unusual screen ratios (e.g., TVs or ultra-wide monitors).       | **[Open `wide.html`](https://siddhantdg.github.io/Claverpage/wide.html)**      |

---

## ✨ Features Showcase

Claverpage is packed with features designed to enhance your browsing workflow.

| Dynamic Search & Suggestions                                       | Organized Shortcut Modals                                            |
| ------------------------------------------------------------------ | -------------------------------------------------------------------- |
| <img src=".github/assets/feature-search.png" alt="Search Feature"> | <img src=".github/assets/feature-modal.png" alt="Modal Feature">     |
| Switch search engines on the fly and get live search suggestions.  | Access large collections of links in clean, full-screen modals.      |

*(**Action for you:** Take two screenshots that show these features. For the first, click on the search bar. For the second, click the "Utilities" button to open the modal. Save them in a `.github/assets/` folder and update the `src` links.)*

## 🛠️ Key Features at a Glance

*   **Dynamic Search Engine:** Switch between Google, Bing, DuckDuckGo, and more on the fly.
*   **Live Search Suggestions:** Get instant search suggestions as you type.
*   **JSON-Powered Shortcuts:** Easily add, remove, and categorize links by editing a single `shortcuts.json` file.
*   **Modern UI/UX:** A sleek dark-mode interface with smooth animations and a responsive design.
*   **Smart Categorization:** Organize shortcuts into main-screen blocks and full-screen modals.
*   **Lightweight & Fast:** Built with pure vanilla HTML, CSS, and JS for near-instant load times.

## 🔧 Configuration

Customizing your shortcuts is incredibly simple. All links and their categories are managed in the **`shortcuts.json`** file.

1.  Open `shortcuts.json`.
2.  Find the category you want to edit (e.g., `"tools"`, `"productivity"`).
3.  Add or remove shortcut objects. Each object needs a `name`, `url`, and `icon` link.

```json
{
  "tools": [
    { 
      "name": "Gmail", 
      "url": "https://mail.google.com", 
      "icon": "https://www.google.com/s2/favicons?sz=64&domain=gmail.com" 
    }
  ]
}
```

## 📜 License & Usage Guidelines

This project is the first I've ever built and shared, and it holds a special place for me. As such, it is licensed under a **Custom License**. Please respect the following terms:

*   ✔️ **You are welcome to:**
    *   View and inspect the source code for learning purposes.
    *   Fork the repository for personal experimentation.
    *   Use any of the live GitHub Pages links as your personal browser homepage.

*   ❌ **You are strictly not permitted to:**
    *   Modify and create derivative works from this code.
    *   Redistribute or republish this code, in part or in whole, elsewhere without my explicit written permission.

## 📞 Contact

If you have any questions, feel free to reach out to me at [siddhantdigraje77@gmail.com](mailto:siddhantdigraje77@gmail.com).

---
<p align="center">
Made with ❤️ by Siddhant
</p>
