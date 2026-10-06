# Image Builder

> The missing image builder of skillicons.dev

A lightweight web editor that lets you select, configure, and export [Skill Icons](https://skillicons.dev) for your GitHub README or résumé.

## ✨ Features

- **Icon Picker** – Browse and toggle from 200+ official Skill Icons
- **Live Preview** – See your icon set update instantly
- **Theme Support** – Switch between dark and light backgrounds
- **Icons Per Line** – Adjust from 1 to 50 (default: 15)
- **Drag & Drop** – Reorder selected icons manually
- **Alphabetical Sort** – One-click A→Z / Z→A sorting
- **Multiple Export Formats** – Markdown, HTML, and plain URL
- **Copy to Clipboard** – Grab the generated code and paste it anywhere

## 🚀 Usage

No installation required. Just open `index.html` in your browser.

1. Click icons in the left grid to add or remove them
2. Adjust theme and icons-per-line in the right panel
3. Reorder with drag & drop or the sort button
4. Switch between Markdown / HTML / URL tabs
5. Click **Copy Code** and paste it into your README

## 📦 Export Examples

**Markdown**

```md
[![My Skills](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev)
```

**HTML**

```html
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,kubernetes,docker,c,vim" />
  </a>
</p>
```

**URL**

```
https://skillicons.dev/icons?i=js,html,css&theme=light&perline=10
```

## 🛠 Tech Stack

- Pure HTML + CSS + JavaScript
- Zero dependencies
- Icons served by [skillicons.dev](https://skillicons.dev)

## 📄 Notes

This project is only a configuration generator for Skill Icons.  
All icon rights belong to their respective owners.  
To request a new icon, please open an issue on [skill-icons Repo](https://github.com/tandpfun/skill-icons).

---

*The missing image builder of skillicons.dev*
