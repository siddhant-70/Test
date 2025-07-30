<div align="center">
  <img src=".github/assets/claverpage-showcase.png" alt="Claverpage Showcase Banner" width="800"/>
</div>

# Claverpage ✨

<div align="center">

[![License](https://img.shields.io/badge/License-Custom-blue.svg)](LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/siddhantdg/Claverpage.svg)](https://github.com/siddhantdg/Claverpage/commits/main)
[![Repo size](https://img.shields.io/github/repo-size/siddhantdg/Claverpage.svg)](https://github.com/siddhantdg/Claverpage)

A modern, dynamic, and customizable browser startpage with multiple search engines, modular shortcuts, and a sleek, animated UI.

**[➡️ View Live Demo](https://siddhantdg.github.io/Claverpage/)**

</div>

---

Welcome to Claverpage! This isn't just a static page; it's a fully-featured, productivity-focused browser homepage designed for speed and style. It serves as a personal dashboard to launch you into your web activities, combining aesthetics with powerful functionality.

## 🚀 Key Features

*   ⚡ **Dynamic Search Engine:** Switch between Google, Bing, DuckDuckGo, and more on the fly directly from the homepage.
*   💡 **Live Search Suggestions:** Get instant, helpful search suggestions from Google as you type, making searching faster and more efficient.
*   🧩 **JSON-Powered Shortcuts:** Easily add, remove, and categorize all your favorite links by editing a single, simple `shortcuts.json` file. No need to touch the HTML!
*   🎨 **Modern UI/UX:** A sleek dark-mode interface with smooth, meaningful animations, a glassmorphism blur effect, and a fully responsive design that looks great on any screen.
*   🗂️ **Smart Categorization:** Organize shortcuts into primary blocks on the main screen or into full-screen modals for larger collections, keeping your dashboard clean and uncluttered.
*   💨 **Lightweight & Fast:** Built with pure HTML, CSS, and vanilla JavaScript for near-instant load times.

## 🎬 In Action

*(Here you would embed your GIF showing the dynamic features)*

<img src=".github/assets/claverpage-demo.gif" alt="Claverpage Demo GIF"/>

## 🔧 Configuration

Customizing your shortcuts is incredibly simple. All links and their categories are managed in the `shortcuts.json` file.

1.  Open the `shortcuts.json` file.
2.  Find the category you want to edit (e.g., `"tools"`, `"productivity"`).
3.  Add or remove shortcut objects. Each object needs a `name`, `url`, and `icon` link.

```json
{
  "tools": [
    { 
      "name": "Gmail", 
      "url": "https://mail.google.com", 
      "icon": "https://www.google.com/s2/favicons?sz=64&domain=gmail.com" 
    },
    { 
      "name": "GitHub", 
      "url": "https://github.com", 
      "icon": "https://www.google.com/s2/favicons?sz=64&domain=github.com" 
    }
    // ...add more tools here
  ],
  "social": [
    // ...add social links here
  ]
}
```

## 📜 Usage Guidelines & License

This project is licensed under a **Custom License**. I'm thrilled you're checking out my project! Here’s what that means for you:

*   ✔️ **You are free to:**
    *   View and inspect the source code.
    *   Fork the repository for personal experimentation and learning.
    *   Use the [live GitHub Pages link](https://siddhantdg.github.io/Claverpage/) as your personal browser homepage.

*   ❌ **You are not permitted to:**
    *   Modify and create derivative works from this code.
    *   Redistribute or republish this code elsewhere without my explicit written permission.

## 📞 Contact

If you have any questions or need permission for usage beyond what is outlined above, feel free to reach out to me at [siddhantdigraje77@gmail.com](mailto:siddhantdigraje77@gmail.com).

---
<p align="center">
Made with ❤️ by Siddhant
</p>
