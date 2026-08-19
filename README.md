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
In `styles.css`, change `--accent: #1f3a5f;` and related `--accent-*` variables in the `:root` block.

### Add/remove sections
Each section is wrapped in `<section class="section" id="...">`. Copy a section block and modify.

---

## Design System

| Token | Value |
|-------|-------|
| `--bg-base` | `#f9f9fc` |
| `--accent` | `#1f3a5f` (deep navy) |
| `--accent-dark` | `#142943` (hover states) |
| `--text-primary` | `#16213a` |
| `--font-display` | Manrope (600/650/700) |
| `--font-body` | Inter |
| `--font-mono` | Inter |
