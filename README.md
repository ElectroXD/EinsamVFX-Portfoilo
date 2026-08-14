# EinsamVFX-Portfoilo
A portfolio website made for Einsam, showcasing his video editing work, experience, achievements, and creative journey

# Einsam — Creative Video Editor Portfolio

> A cinematic, interactive portfolio website made for **Einsam**, a professional video editor and content creator.

---

## Overview

This repository contains the official portfolio website created for **Einsam**, a professional video editor who specializes in editing videos and creating content that keeps viewers engaged.

The website was designed to present Einsam's editing work, achievements, experience, clients, creative process, and overall visual identity through a modern and cinematic web experience.

Rather than following a traditional portfolio layout, the website focuses heavily on motion, interactive elements, video presentation, and a dark premium aesthetic to reflect the creative nature of video editing.

---

## About Einsam

**Einsam** is a professional video editor and content creator with **3+ years of experience** working with creators and brands.

### Personal Tagline

> **Let's Create Something Amazing**

### Description

> I'm Einsam. I enjoy editing videos and creating content that keeps the viewer hooked!

---

## Achievements

| Achievement | Result |
|------------|--------|
| Videos Edited | **400+** |
| Views Generated | **400M+** |
| Creators & Brands Worked With | **15+** |
| Experience | **3+ Years** |

---

## Clients & Creators

Einsam has worked with a variety of creators and brands, including:

- Porosh
- RyanPictures
- Freshi
- FlingHD
- Ben Balla
- Beem Gaming
- Based
- Phat Ash & Friends
- Pexto

The website includes an interactive **"Trusted by creators & brands"** showcase to highlight these collaborations.

---

## Portfolio & Showreel

The homepage includes a dedicated cinematic **Showreel** experience designed to immediately introduce visitors to Einsam's editing style.

The video experience includes:

- Custom video interface
- Custom play/pause controls
- Custom mute control
- Interactive video timeline
- Responsive video presentation
- Thumbnail/poster support
- Minimal UI
- No unnecessary third-party video-player branding

A separate **`portfolio.html`** page is planned for a future update and will contain the complete collection of Einsam's edited projects.

---

## Design Direction

The website follows a dark, cinematic, and high-end visual direction inspired by modern creative portfolios and motion-design websites.

### Visual characteristics

- Dark cinematic background
- Premium typography
- Minimal interface
- Orange accent system
- Interactive motion graphics
- Smooth transitions
- Video-focused layouts
- Responsive design
- Creative micro-interactions

### Primary Brand Color

`#FC8003`

The orange accent is used carefully throughout the interface for highlights, interactions, borders, active states, and visual emphasis.

---

## Interactive Experience

The website includes a number of custom interactions designed to make the portfolio feel more alive.

### Custom Cursor

A custom cursor system is used for desktop pointer devices.

Normal cursor:

`assets/cursor/cursor.png`

Interactive/hover cursor:

`assets/cursor/hand.png`

The cursor automatically changes when interacting with clickable elements.

---

### Client Marquee

The **Trusted by creators & brands** section features an interactive horizontal marquee with:

- Infinite movement
- Drag interaction
- Touch support
- Responsive behavior
- Creator cards
- Subscriber information
- Smooth hover behavior

---

### Motion Graphics Background

The website uses a custom animated line-based background system inspired by modern motion-design and generative network visuals.

The background is built around:

- Interconnected orange lines
- Geometric network structures
- Large-scale formations
- Subtle motion
- Parallax depth
- Scroll-based movement
- Cinematic orange highlights

The system is intentionally designed without relying on a generic particle background.

---

### FAQ Interaction

The FAQ section includes animated accordion interactions with smooth transitions and visual feedback.

---

## Technology

The project is intentionally built with a lightweight frontend stack.

### Core

- HTML5
- CSS3
- Vanilla JavaScript

### No Frameworks

This project does **not** rely on:

- React
- Vue
- Angular
- Next.js
- Tailwind CSS
- Bootstrap

The goal is to keep the website lightweight, maintainable, and easy to deploy as a static website.

---

## Project Structure

```text
EINSAM PORTFOLIO/
│
├── assets/
│   ├── clients/
│   │   ├── logos/
│   │   └── videos/
│   │
│   ├── cursor/
│   │   ├── cursor.png
│   │   └── hand.png
│   │
│   ├── favicon/
│   │   └── MainLogoRounded.png
│   │
│   ├── icons/
│   │   ├── play.png
│   │   └── pause.png
│   │
│   ├── images/
│   │   ├── Einsam-Text.png
│   │   └── MainLogo.webp
│   │
│   └── thumbnail/
│       └── einsam-showreel-thumbnail.png
│
├── css/
│   ├── animations.css
│   ├── responsive.css
│   └── style.css
│
├── js/
│   ├── portfolio.js
│   └── script.js
│
├── index.html
├── PROJECT_CONTEXT.md
└── README.md
