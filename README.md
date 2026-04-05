<div align="center">

# ⚡ Code Flow Visualizer

### Transform your code into beautiful, interactive flowcharts — instantly.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Site-8b5cf6?style=for-the-badge)](https://anshmajumdar121.github.io/code-flow-visualizer/)
[![Playground](https://img.shields.io/badge/🎮_Playground-Try_Now-a78bfa?style=for-the-badge)](https://anshmajumdar121.github.io/code-flow-visualizer/playground.html)
[![License](https://img.shields.io/badge/License-BSL_1.1-red?style=for-the-badge)](LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-anshmajumdar121-181717?style=for-the-badge&logo=github)](https://github.com/anshmajumdar121)

</div>

---

## 🌐 Live URL

> **Landing Page:** https://anshmajumdar121.github.io/code-flow-visualizer/

---


---

## 🎬 Demo Preview

> **Try it instantly — no install needed.**
> Paste any Python function and watch it become a flowchart in real time.

<div align="center">

### 📝 Sample Input

```python
def factorial(n):
    if n <= 1:
        return 1
    return n * factorial(n - 1)
```

### ⬇️ Becomes This Flowchart

<table align="center"><tr><td align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="320" height="420" viewBox="0 0 320 420" style="background:#0d1117;border-radius:12px;border:1px solid #30363d">
  <defs>
    <marker id="arr" markerWidth="8" markerHeight="8" refX="4" refY="4" orient="auto">
      <path d="M0,0 L8,4 L0,8 Z" fill="#00e5ff"/>
    </marker>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <!-- START -->
  <ellipse cx="160" cy="36" rx="48" ry="20" fill="none" stroke="#00ff88" stroke-width="2" filter="url(#glow)"/>
  <text x="160" y="41" text-anchor="middle" fill="#00ff88" font-family="monospace" font-size="13" font-weight="bold">START</text>
  <!-- Arrow START -> condition -->
  <line x1="160" y1="56" x2="160" y2="86" stroke="#00e5ff" stroke-width="1.5" marker-end="url(#arr)"/>
  <!-- CONDITION diamond -->
  <polygon points="160,90 220,130 160,170 100,130" fill="none" stroke="#ff2d78" stroke-width="2" filter="url(#glow)"/>
  <text x="160" y="126" text-anchor="middle" fill="#ff2d78" font-family="monospace" font-size="10">n &lt;= 1?</text>
  <text x="160" y="140" text-anchor="middle" fill="#ff2d78" font-family="monospace" font-size="9">(condition)</text>
  <!-- YES label -->
  <text x="84" y="142" text-anchor="middle" fill="#00ff88" font-family="monospace" font-size="10">YES</text>
  <!-- NO label -->
  <text x="236" y="142" text-anchor="middle" fill="#a855f7" font-family="monospace" font-size="10">NO</text>
  <!-- YES path -> return 1 -->
  <line x1="100" y1="130" x2="56" y2="130" stroke="#00e5ff" stroke-width="1.5"/>
  <line x1="56" y1="130" x2="56" y2="230" stroke="#00e5ff" stroke-width="1.5" marker-end="url(#arr)"/>
  <!-- return 1 box -->
  <rect x="16" y="230" width="82" height="36" rx="6" fill="none" stroke="#a855f7" stroke-width="2" filter="url(#glow)"/>
  <text x="57" y="252" text-anchor="middle" fill="#a855f7" font-family="monospace" font-size="11">return 1</text>
  <!-- NO path -> return n*factorial -->
  <line x1="220" y1="130" x2="264" y2="130" stroke="#00e5ff" stroke-width="1.5"/>
  <line x1="264" y1="130" x2="264" y2="230" stroke="#00e5ff" stroke-width="1.5" marker-end="url(#arr)"/>
  <!-- return n*f(n-1) box -->
  <rect x="202" y="230" width="108" height="44" rx="6" fill="none" stroke="#a855f7" stroke-width="2" filter="url(#glow)"/>
  <text x="256" y="249" text-anchor="middle" fill="#a855f7" font-family="monospace" font-size="10">return n *</text>
  <text x="256" y="263" text-anchor="middle" fill="#a855f7" font-family="monospace" font-size="10">factorial(n-1)</text>
  <!-- Both paths -> END -->
  <line x1="57" y1="266" x2="57" y2="360" stroke="#00e5ff" stroke-width="1.5"/>
  <line x1="57" y1="360" x2="140" y2="360" stroke="#00e5ff" stroke-width="1.5" marker-end="url(#arr)"/>
  <line x1="256" y1="274" x2="256" y2="360" stroke="#00e5ff" stroke-width="1.5"/>
  <line x1="256" y1="360" x2="180" y2="360" stroke="#00e5ff" stroke-width="1.5" marker-end="url(#arr)"/>
  <!-- END -->
  <ellipse cx="160" cy="360" rx="40" ry="20" fill="none" stroke="#00ff88" stroke-width="2" filter="url(#glow)"/>
  <text x="160" y="365" text-anchor="middle" fill="#00ff88" font-family="monospace" font-size="13" font-weight="bold">END</text>
</svg>
</td></tr></table>

<br/>

[![▶ Try it Live in the Playground](https://img.shields.io/badge/▶_Try_it_Live-Open_Playground-00e5ff?style=for-the-badge&labelColor=0d1117)](https://anshmajumdar121.github.io/code-flow-visualizer/playground.html)

</div>

## 📖 About

**Code Flow Visualizer** is a fully client-side, browser-based tool that converts your code into clean, interactive flowcharts in real time. No backend. No installation. Just open and start visualizing.

Built entirely with **HTML, CSS, and vanilla JavaScript** — zero frameworks, zero dependencies, zero runtime costs. Everything runs in your browser.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🌐 **Multi-Language Support** | Python, JavaScript, Java, C++, and more |
| 📐 **Auto-Layout Engine** | Smart automatic graph layout — no manual positioning |
| 🐛 **Step Debugger** | Walk through loops and branches line by line |
| 📤 **Export & Share** | Export as PNG, SVG, or generate a shareable link |
| 💬 **Annotations** | Add notes to any node to explain logic |
| 🔒 **Secure by Default** | All code processed in-memory — nothing stored |
| ⚡ **Zero Dependencies** | Pure HTML + CSS + JS — works fully offline |
| 📱 **Responsive Design** | Works on desktop, tablet, and mobile |

---

## 🗂️ Project Structure

```
code-flow-visualizer/
├── index.html        # Landing / Hero page
├── playground.html   # Interactive visualizer app (full JS engine inside)
├── LICENSE           # Business Source License 1.1
└── README.md         # You are here
```

> **Note:** All JavaScript logic — the flowchart engine, AST parser, step debugger, and canvas renderer — lives inside `playground.html` as self-contained `<script>` blocks. This keeps the project dependency-free and instantly deployable with zero build steps.

---

## 🚀 How It Works

```
Step 1 — Paste Code     →  Drop Python, JS, Java, C++ or pseudocode into the editor
Step 2 — Parse & Layout →  An AST (Abstract Syntax Tree) is built; flowchart auto-generates
Step 3 — Explore Steps  →  Click any node to inspect variable state and step through execution
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (Glassmorphism, Grid, Animations) |
| Logic | Vanilla JavaScript (AST parser, canvas renderer, step debugger) |
| Hosting | GitHub Pages |

No React. No Node.js. No build tools. Clone and open — it just works.

---

## 🧑‍💻 Running Locally

```bash
# Clone the repository
git clone https://github.com/anshmajumdar121/code-flow-visualizer.git

# Navigate into the project
cd code-flow-visualizer

# Open in your browser — no build step needed!
open index.html
```

Or simply visit the **[live GitHub Pages URL](https://anshmajumdar121.github.io/code-flow-visualizer/)**.

---

## 🔐 License & Usage Restrictions

This project is protected under the **Business Source License 1.1 (BSL 1.1)**.

| Permission | Status |
|---|---|
| View & study the code | ✅ Allowed |
| Personal / non-production use | ✅ Allowed |
| Copy or redistribute | ❌ Not allowed |
| Re-host or public fork | ❌ Not allowed |
| Commercial use without license | ❌ Not allowed |
| Create derivative products | ❌ Not allowed |

> Converts to **MIT License** four years after the first public release date.
>
> 📄 Full license: [LICENSE](LICENSE)
>
> 💼 Commercial licensing: **majumdar82@gmail.com**

---

## 💖 Support the Project

If Code Flow Visualizer saved you time or helped you learn, consider supporting:

| Method | Details |
|---|---|
| 🇮🇳 UPI | `majumdar82@okhdfcbank` |
| 💳 PayPal | `majumdar82@gmail.com` |

Every contribution keeps this project free for everyone ❤️

---

## 👤 Author

**Ansh Majumdar** — Systems Thinker | Problem Solver | Builder

- 🔗 GitHub: [@anshmajumdar121](https://github.com/anshmajumdar121)
- 💡 Focus: Scalable backends, data-driven systems, real-world impact
- 🧠 Philosophy: *"I don't just write code — I architect solutions. Every line has a purpose."*

---

<div align="center">

Made with ❤️ by **Ansh Majumdar** &nbsp;|&nbsp; © 2026 Code-Visualizer

[![Visit Site](https://img.shields.io/badge/Visit-Code_Flow_Visualizer-8b5cf6?style=flat-square)](https://anshmajumdar121.github.io/code-flow-visualizer/)

</div>
