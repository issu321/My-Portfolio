# Mohammed Usman — AI & ML Portfolio

> **Driven by Courage. Powered by Innovation. Focused on Impact.**

A fully responsive, single-file portfolio website built with pure **HTML, CSS, and JavaScript** — featuring a unique **Futuristic Ancient Fusion** aesthetic, blur glassmorphism effects, and the **50-30-20 color rule**.

---

## 🌐 Live Preview

Open `index.html` in any modern browser. No build tools, no dependencies, no server required.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Animated Particle Background** | Floating bronze & cyan particles with dynamic connection lines |
| **Blur Glassmorphism** | `backdrop-filter: blur(20px)` on every card with ancient border styling |
| **Typing Effect** | Hero title types out character-by-character on load |
| **Scroll Animations** | Elements fade in smoothly as you scroll down the page |
| **3D Hover Tilt** | Cards tilt toward your mouse cursor for an interactive feel |
| **Counter Animation** | Stats animate from 0 to their final value |
| **Parallax Hero** | Hero content moves slower than scroll for depth perception |
| **Fully Responsive** | Optimized for Desktop, Tablet, and Mobile with hamburger navigation |
| **Smooth Scroll** | Click any nav link to glide smoothly to that section |
| **Custom Scrollbar** | Styled scrollbar matching the ancient bronze theme |
| **Text Selection** | Cyan highlight on text selection |

---

## 🎨 Design System

**Theme:** *Futuristic Ancient Fusion* — blending ancient aesthetics (Cinzel font, bronze tones) with futuristic tech vibes (Orbitron font, cyan glow).

### 50-30-20 Color Rule

| Role | Color | Hex | Usage |
|------|-------|-----|-------|
| **50% Base** | Deep Obsidian | `#0a0a0f` | Background, primary surface |
| **30% Secondary** | Burnished Bronze | `#8b6914` | Borders, accents, buttons |
| **20% Accent** | Cyan Glow | `#00d4ff` | Highlights, hover states, links |

### Typography

| Font | Role | Usage |
|------|------|-------|
| **Cinzel** | Ancient | Headings, names, section titles |
| **Inter** | Modern | Body text, descriptions, buttons |
| **Orbitron** | Tech | Labels, badges, stats, code tags |

---

## 📁 Project Structure

```
portfolio/
├── index.html          # Complete portfolio (HTML + CSS + JS in one file)
├── pict.png            # Your profile photo (replace with your own)
└── README.md           # This file
```

> **Note:** This is a **single-file** portfolio. All HTML, CSS, and JavaScript are self-contained in `index.html` for maximum portability and zero dependencies.

---

## 🚀 Quick Start

### 1. Clone or Download

```bash
git clone https://github.com/issu321/portfolio.git
cd portfolio
```

### 2. Add Your Photo

Replace `pict.png` with your own profile photo. Keep the filename as `pict.png` or update the `src` attribute in the About section:

```html
<!-- Line ~340 in index.html -->
<img src="pict.png" alt="Mohammed Usman">
```

### 3. Open in Browser

Simply double-click `index.html` or serve it locally:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

---

## 🛠️ Customization Guide

### Update Personal Information

All your info is already pre-filled. To make changes, edit these sections in `index.html`:

| Section | Location | What to Edit |
|---------|----------|--------------|
| **Name** | Hero Section | `<h1 class="hero-name">` |
| **Title** | Hero Section | `<p class="hero-title">` |
| **Bio** | Hero & About | `<p class="hero-desc">` and About paragraphs |
| **Location** | Hero Section | `<div class="hero-location">` |
| **Email** | Contact Section | `<a href="mailto:...">` |
| **Phone** | Contact Section | `<a href="tel:...">` |
| **GitHub** | Multiple | `href="https://github.com/issu321"` |
| **Skills** | Skills Section | `<span class="skill-tag">` elements |
| **Projects** | Projects Section | Cards with titles, descriptions, tech tags |

### Update Project Links

Replace placeholder GitHub links with your actual repositories:

```html
<!-- Example: AI Jarvis Assistant -->
<a href="https://github.com/issu321/ai-jarvis" target="_blank" class="btn-view">View Project</a>
<a href="https://github.com/issu321/ai-jarvis" target="_blank" class="btn-code">Source Code</a>
```

### Update Stats

Change the animated counters in the About section:

```html
<span class="stat-number" data-count="20">0</span>
<!-- Change data-count to your actual number -->
```

### Change Colors

Modify CSS variables at the top of the `<style>` block:

```css
:root {
    --color-50: #0a0a0f;    /* 50% - Background */
    --color-30: #8b6914;    /* 30% - Secondary */
    --color-20: #00d4ff;    /* 20% - Accent */
}
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout Changes |
|------------|----------------|
| **> 1024px** | Full desktop: side-by-side About grid, multi-column projects |
| **768px - 1024px** | Tablet: stacked About, 2-column skills, hamburger menu |
| **< 768px** | Mobile: single column everything, full-width buttons, hamburger nav |
| **< 480px** | Small mobile: compact typography, single column focus cards |

---

## 🧰 Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Flexbox, Grid, Animations, Backdrop filters
- **Vanilla JavaScript** — Canvas API, Intersection Observer, Event listeners
- **Google Fonts** — Cinzel, Inter, Orbitron
- **No frameworks. No libraries. No build step.**

---

## 🎯 Performance

- ✅ **Single file** — Only 1 HTTP request
- ✅ **Zero dependencies** — No npm, no webpack, no bundler
- ✅ **Optimized fonts** — Google Fonts with `display=swap`
- ✅ **Lightweight** — ~53KB total (HTML + inline CSS + inline JS)
- ✅ **GPU accelerated** — `transform` and `opacity` for animations
- ✅ **Lazy loading ready** — Add `loading="lazy"` to images if needed

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

Feel free to fork, modify, and use it for your own portfolio!

---

## 🤝 Connect

Built with ♥ by **Mohammed Usman**

- 🌐 **Portfolio:** [issu321.github.io](https://github.com/issu321)
- 💻 **GitHub:** [@issu321](https://github.com/issu321)
- 📧 **Email:** [jaafreeusman@gmail.com](mailto:jaafreeusman@gmail.com)
- 📱 **Phone:** +91 88842 94749 / +91 86187 56284
- 📍 **Location:** Bangalore, Karnataka, India

---

> **"Building tech that accelerates human capability."**
