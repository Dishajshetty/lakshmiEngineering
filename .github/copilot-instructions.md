# Project Instructions

## Project structure
- This is a static website; there is no package manifest, build system, or automated test suite in the repository.
- `index.html` is the primary Lakshmi Engineering website. `index3.html` is a separate standalone sample page.
- The main site stylesheet is `styles/style.css`; image assets are stored under `styles/images/`.
- The main page uses Bootstrap 5 and Font Awesome from CDNs, plus inline JavaScript for navigation, scrolling, and gallery pagination. It also references GSAP and AOS.

## Making changes
- Keep changes focused on the relevant page and preserve the existing HTML/CSS/vanilla JavaScript approach unless the task calls for a different approach.
- Reuse existing CSS classes and assets where practical. Keep image paths relative to the HTML document.
- When changing navigation or gallery behavior, check the corresponding IDs, links, and inline script in `index.html` together.
- Avoid introducing a build tool or dependency for a small static-site change.

## Validation
- There are no configured automated tests. Validate changed pages in a browser, checking desktop and mobile layouts and any affected interactions.
- For asset or link changes, verify the referenced local paths and page anchors resolve correctly.
