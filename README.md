# CodeClash

CodeClash is a modern, animation-heavy landing page for a coding competition / challenge platform.  
It’s built to feel fast, polished, and a little dramatic — with smooth transitions, bold typography, and an experience that feels more like a product than a simple static site.

🌐 **Live Site:** https://codeclash-chirag.netlify.app/

---

## ✨ Features

- **Hero Section with Motion**
  - Eye-catching hero with animated text and subtle motion to grab attention immediately.
- **Section-Based Layout**
  - Clear sections for problem themes, event/track details, how-it-works, and calls-to-action.
- **Smooth Animations**
  - Micro-interactions and scroll-based transitions that keep the page feeling alive.
- **Responsive Design**
  - Fully responsive layout that works across desktop, tablet, and mobile devices.
- **Reusable Components**
  - Modular components for cards, buttons, sections, and layout to keep the codebase clean.

> _Note: You can tweak the copy to match the exact structure/content of your current CodeClash page._

---

## 🛠 Tech Stack

- **Framework:** React (with Vite as the build tool)
- **Styling:** Tailwind CSS
- **Animations:** GSAP / Framer Motion (depending on what you used)
- **Deployment:** Netlify

If you used anything extra (e.g., React Icons, custom fonts, etc.), you can extend this list.

---

## 📂 Project Structure

A typical structure for this project looks like:

```bash
CodeClash/
├── public/
│   └── assets/          # Static assets (images, icons, etc.)
├── src/
│   ├── components/      # Reusable UI components (buttons, cards, sections)
│   ├── sections/        # Page sections (Hero, About, Tracks, Footer, etc.)
│   ├── styles/          # Global styles / Tailwind config (if any custom files)
│   ├── App.jsx          # Main app entry
│   └── main.jsx         # React + Vite bootstrap
├── package.json
├── tailwind.config.cjs / tailwind.config.js
├── postcss.config.cjs / postcss.config.js
└── vite.config.js
