# Capstone Project — YouTube-style UI

Live demo: (add your GitHub Pages or hosted link here)

A responsive, accessible, and component-driven front-end project that recreates a YouTube-style interface using plain HTML, CSS, and static assets. This repository demonstrates UI/UX skills, semantic HTML, responsive layout techniques, and CSS componentization.

---

## Project Overview

This project is a single-page front-end application built with static HTML and CSS. It replicates common parts of a video platform UI — header/navigation, sidebar, video grid/listing, and responsive behaviors — to show practical front-end skills and attention to detail.

Key goals:

- Build a pixel-accurate, responsive layout without a JavaScript framework.
- Organize styles into modular CSS files for maintainability.
- Use semantic HTML for accessibility and SEO friendliness.
- Provide a clean repo that's easy for recruiters and engineers to review.

## What to look for

- Clean, semantic HTML structure in `youtube.html`.
- Modular CSS in `styles/` (files: `general.css`, `header.css`, `sidebar.css`, `videos.css`, `practice-header.css`).
- Well-organized assets under `img/` and `icons/`.
- Responsive grid/list for videos and a fully functional navigation/header UI.

## Features

- Responsive header with search and user area.
- Collapsible sidebar (CSS-driven layout that adapts to widths).
- Video cards with thumbnail, title, channel, and meta information.
- Reusable CSS components and utility classes.
- Easily themeable colors and spacing variables in CSS.

## Tech Stack

- HTML5
- CSS3 (modular architecture)
- Static assets (SVG/PNG icons and images)

## Setup (for reviewers)

1. Clone the repo:

   git clone https://github.com/Gagan-TW/capstone-project.git

2. Open `youtube.html` in a browser (no build step required).

Optional: serve locally with a static server (recommended to test relative paths):

   # Using Python 3
   python -m http.server 8000

   # Or using Node.js (http-server)
   npx http-server -c-1

Then open http://localhost:8000/youtube.html in your browser.

## Skills Demonstrated

- Responsive design and mobile-first CSS
- Semantic HTML and accessible markup
- Component-based CSS organization
- Visual layout: Flexbox and CSS Grid
- Attention to UI details: spacing, typography, iconography
- Project structuring for easy review by recruiters

## How to present this to recruiters

1. Host the project on GitHub Pages (Settings → Pages) and paste the live demo link at the top of this README.
2. Add 2–3 screenshots or a short 20–30s demo GIF showcasing the responsive behavior and key components.
3. In your cover message to recruiters, include a one-line summary and the direct link to the demo and repository.

Suggested one-liner for messages:

> "Interactive YouTube-style front-end (HTML/CSS) — responsive, accessible UI demonstrating componentized CSS and layout skills. Live demo: <link>"

## Next steps (optional improvements you can implement quickly)

- Add a small amount of JavaScript to toggle the sidebar and improve interactivity.
- Add unit or visual regression tests with a tiny test runner if you want to demonstrate testing knowledge.
- Deploy to GitHub Pages and attach screenshots and a short demo video in the README.

## License

Distributed under the MIT License. See `LICENSE` for details (or add one if you want to include it).

## Contact

Your Name — your.email@example.com

LinkedIn: https://www.linkedin.com/in/your-profile

Repository: https://github.com/Gagan-TW/capstone-project
