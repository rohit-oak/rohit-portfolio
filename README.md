# Rohit A. Oak — Portfolio

**Platform Engineering · BFSI · Enterprise Systems**

A recruiter-facing portfolio built to reposition from enterprise BFSI delivery toward Platform Engineering, Technical Program Management, and AI-assisted engineering workflows.

---

## Deploying to Netlify

### Option 1: Drag & Drop (Fastest)
1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag the entire `rohit-portfolio/` folder onto the Netlify dashboard
3. Your site is live instantly

### Option 2: GitHub + Netlify CI
1. Push this folder to a GitHub repo
2. Connect the repo in Netlify → "New site from Git"
3. Build command: *(leave blank — static site)*
4. Publish directory: `.` (root of the folder)
5. Deploy

---

## File Structure

```
rohit-portfolio/
├── index.html        ← Main portfolio page
├── styles.css        ← All styles (CSS custom properties, responsive)
├── script.js         ← Nav, scroll reveal, mobile menu
├── assets/           ← Add screenshots / workflow images here
│   └── (placeholder)
└── README.md         ← This file
```

---

## Customisation Guide

### Update contact details
In `index.html`, search for `oak.rohit@gmail.com` and `+91 9967181489` to update.

### Add workflow screenshots
Place PNG/WEBP images in `/assets/` and reference them in the `.arch-diagram` section or new sections as needed.

### Adjust accent colour
In `styles.css`, change `--teal-bright: #5ec5b8;` and related teal variables.

### Add/remove sections
Each section is wrapped in `<section class="section" id="...">`. Copy a section block and modify.

---

## Design System

| Token | Value |
|-------|-------|
| `--bg-base` | `#0c0f0f` |
| `--teal-bright` | `#5ec5b8` |
| `--font-display` | Syne (700/800) |
| `--font-body` | DM Sans |
| `--font-mono` | DM Mono |
