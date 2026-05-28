<div align="center">

# 🖼️ wireframe-to-code

### Convert wireframes & UI designs into pixel-perfect, production-ready code

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange.svg)](https://claude.ai)
[![Antigravity IDE](https://img.shields.io/badge/Antigravity-IDE-blue.svg)](#)
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

<br/>

> Upload any wireframe, Figma screenshot, sketch, or UI mockup —
> get back clean, structured, production-ready code in your chosen tech stack.
> Powered by **Claude AI** · Compatible with **Antigravity IDE**

<br/>

[🚀 Quick Start](#-quick-start) · [📦 Installation](#-installation) · [🎯 Tech Stacks](#-supported-tech-stacks) · [🤝 Contributing](#-contributing)

</div>

---

## 📌 Table of Contents

- [What This Skill Does](#-what-this-skill-does)
- [How It Works](#-how-it-works)
- [Supported Tech Stacks](#-supported-tech-stacks)
- [Quick Start](#-quick-start)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [What Gets Generated](#-what-gets-generated)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ What This Skill Does

Most developers waste hours translating designs into code — manually guessing spacing, recreating layouts, and matching colors. **wireframe-to-code** eliminates that.

Upload any design image and this skill will:

- 🔍 **Deeply analyze** the design — layout, colors, spacing, typography, every component
- 🛠️ **Ask your preferred stack** — Angular, React, Vue, or plain HTML
- ⚡ **Generate complete code** — structured, clean, and pixel-accurate
- 🔄 **Iterate instantly** — refine any part based on your feedback

---

## ⚙️ How It Works

```
┌─────────────────┐     ┌──────────────────┐     ┌─────────────────────┐
│  Upload Image   │────▶│  AI Analysis     │────▶│  Production Code    │
│  (wireframe /   │     │  · Layout        │     │  · Component files  │
│   screenshot /  │     │  · Colors        │     │  · SCSS/Tailwind    │
│   mockup)       │     │  · Typography    │     │  · Pixel-perfect    │
│                 │     │  · Components    │     │  · Ready to use     │
└─────────────────┘     └──────────────────┘     └─────────────────────┘
```

**Step 1** — Upload your design image to Claude or Antigravity IDE
**Step 2** — Skill analyzes every detail of the UI
**Step 3** — Choose your tech stack (Angular, React, Vue, HTML)
**Step 4** — Receive complete, structured, production-ready code
**Step 5** — Iterate and refine with simple feedback

---

## 🎯 Supported Tech Stacks

| Category | Options |
|---|---|
| **Frameworks** | Angular (TypeScript) · React (TS/JS) · Vue 3 (Composition API) · Plain HTML/JS |
| **Styling** | SCSS/SASS · Tailwind CSS · CSS Modules · Plain CSS · Styled Components |
| **UI Libraries** | Angular Material · PrimeNG · shadcn/ui · Ant Design · Material UI (MUI) |
| **Icon Libraries** | Lucide · Material Icons · Font Awesome |

---

## 🚀 Quick Start

```bash
# 1. Install the skill (see Installation section below)

# 2. Upload your wireframe or screenshot to Claude / Antigravity IDE

# 3. Use one of these prompts:
"Convert this wireframe to Angular with SCSS"
"Make this design into React with Tailwind"
"Replicate this UI exactly in HTML/CSS"
"Turn this mockup into Vue 3 with CSS Modules"
```

### Example Output Structure (Angular)
```
my-component/
├── my-component.component.ts       # Component logic
├── my-component.component.html     # Template (matches design exactly)
└── my-component.component.scss     # Styles with variables & mixins
```

---

## 📦 Installation

### Option 1 — One-click install (Recommended)
1. Download `wireframe-to-code.skill` from [Releases](../../releases)
2. Open **Claude** → Settings → Skills → Install from file
3. Select the `.skill` file → Done ✅

### Option 2 — Clone the repo
```bash
git clone https://github.com/Bidyut-Das/wireframe-to-code-skill.git
```
Copy the `wireframe-to-code/` folder into your Claude or Antigravity IDE skills directory.

### Option 3 — Manual install
Download the files individually and place them in your skills folder:
```
skills/
└── wireframe-to-code/
    ├── SKILL.md
    └── references/
        ├── angular.md
        ├── react.md
        └── scss-patterns.md
```

---

## 📁 Project Structure

```
wireframe-to-code-skill/
│
├── 📄 README.md                        # You are here
├── 📄 LICENSE                          # MIT License
├── 📦 wireframe-to-code.skill          # Installable skill package
│
└── 📂 wireframe-to-code/
    ├── 📄 SKILL.md                     # Core skill instructions & logic
    └── 📂 references/
        ├── 📄 angular.md               # Angular patterns, modules, Material
        ├── 📄 react.md                 # React/TSX hooks & component patterns
        └── 📄 scss-patterns.md         # Variables, mixins, grid, breakpoints
```

---

## 🔍 What Gets Generated

Every output includes:

| Output | Description |
|---|---|
| 📁 **File tree** | Clear folder and file structure |
| 💻 **Full source code** | Every file, labeled and complete |
| 🎨 **Styles** | SCSS/CSS with variables, mixins, and responsive breakpoints |
| 📖 **Usage guide** | How to integrate into your existing project |
| ⚠️ **Approximation notes** | Transparent about any estimated colors or spacing |

---

## 🗺️ Roadmap

- [x] Angular + SCSS support
- [x] React + TypeScript support
- [x] Vue 3 Composition API support
- [x] Tailwind CSS support
- [ ] Svelte support
- [ ] Next.js / Nuxt.js support
- [ ] Auto color extraction from screenshots
- [ ] Multi-screen / flow support
- [ ] Storybook story generation
- [ ] Unit test generation for components

---

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how you can help:

```bash
# Fork the repo
git fork https://github.com/Bidyut-Das/wireframe-to-code-skill.git

# Create your feature branch
git checkout -b feature/add-svelte-support

# Commit your changes
git commit -m "feat: add Svelte component reference patterns"

# Push and open a Pull Request
git push origin feature/add-svelte-support
```

### Ways to contribute
- 🆕 Add new framework reference files (Svelte, Next.js, Nuxt, etc.)
- 🐛 Fix inaccuracies in generated patterns
- 📖 Improve documentation
- ⭐ Star the repo to show support

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for full details.

```
MIT License — Copyright (c) 2026 Bidyut Das

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software...
```

---

<div align="center">

**Made with ❤️ by [Bidyut Das](https://github.com/Bidyut-Das)**

*Claude Skill · Antigravity IDE Skill*

<br/>

⭐ If this skill helped you, please consider giving it a star!

</div>
