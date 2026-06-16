# Mermaid Local Editor

A lightweight, high-performance, client-side editor for building and exporting Mermaid.js diagrams. Built using Monaco Editor for code input, Tailwind CSS for styling, and native browser APIs for high-resolution rendering and asset exporting.

## 🚀 Live Demo
👉 **[Launch Live Application](ADD_YOUR_GITHUB_PAGES_LINK_HERE)**

---

## 📸 Preview
![Application Screenshot](assets/screenshot.png)

---

## ✨ Features

* **Live Rendering:** Real-time visual updates with integrated performance debouncing.
* **Advanced Code Editor:** Powered by the Monaco Editor (the core engine behind VS Code) featuring syntax distinction and micro-sync states.
* **Viewport Canvas Controllers:** Rich UX supports infinite panning (click-and-drag) and precise scaling/zooming via mouse wheel or quick control badges.
* **Dynamic Styling Skins:** Native application dark mode toggle paired alongside native Mermaid theme engines (Default, Forest, Dark, Neutral, Base).
* **Pro-Grade Export Engine:**
    * **Copy SVG:** Copies clean, un-styled raw vector markup straight to your clipboard.
    * **Download SVG:** Saves independent, scalable vector graphics configurations (`.svg`).
    * **Download PNG:** Vector-to-raster engine exports high-resolution crisp PNG files adjusted for the target theme background.

---

## 🛠️ Architecture & Dependencies

This application is built as a zero-build, static web platform. It leverages open-source utilities streamed through highly reliable edge CDNs:
* [Mermaid.js (v10)](https://mermaid.js.org/) - Diagram parsing and generation framework.
* [Monaco Editor](https://microsoft.github.io/monaco-editor/) - Embedded code IDE.
* [Tailwind CSS](https://tailwindcss.com/) - Utility-first styling composition framework.
* [Lucide Icons](https://lucide.dev/) - Scalable UI iconography.

---

## 📝 Licensing

This project is open-source software licensed under the **MIT License**. 

Independent dependencies fetched via CDN endpoints preserve their corresponding original operational conditions (predominantly MIT/ISC variants). Feel free to clone, modify, and host your own iterations.