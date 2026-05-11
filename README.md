# VAC Global Solutions — Next-Gen ERP Consulting

🌐 **Live Site:**https://vacglobalsolution.netlify.app/

---

## About

VAC Global Solutions is a SaaS-driven ERP consulting firm based in Trichy, Tamil Nadu. This is the official company website showcasing services, client results, and pricing.

---

## Tech Stack

* **Astro 4.x** — Static site framework
* **Three.js r128** — 3D hero scene with wireframe geometry and particles
* **Vanilla CSS** — Custom design system with CSS variables
* **Netlify** — Hosting and deployment

---

## Features

* 3D animated hero with Three.js (floating shapes, particle field, dome glow)
* Scroll-triggered reveal animations
* Animated stat counters
* Infinite client ticker
* Custom cursor
* Fully responsive with mobile menu
* Glassmorphism card design

---

## Project Structure

```bash
Vac-Website-master/
├── src/
│   ├── components/
│   │   ├── Outcomes.astro
│   │   ├── Portfolio.astro
│   │   ├── Pricing.astro
│   │   ├── Process.astro
│   │   └── Services.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── clients/
│   │   │   └── [slug].astro
│   │   ├── about.astro
│   │   ├── erp.astro
│   │   ├── index.astro
│   │   ├── pricing.astro
│   │   ├── process.astro
│   │   ├── services.astro
│   │   └── vac3d.astro
│   └── styles/
├── env.d.ts
├── middleware.ts
├── .gitignore
├── astro.config.mjs
├── package.json
└── README.md
```

---

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev         # http://localhost:4321

# Build for production
npm run build
```

---

## Deployment

Hosted on Netlify. Build settings:

* **Build command:** `npm run build`
* **Publish directory:** `dist`

---

## Contact

📍 Trichy, Tamil Nadu, India
📧 [info@vacglobal.com](mailto:info@vacglobal.com)
📞 +91 98765 43210

© 2025 VAC Global Solutions. All rights reserved.
