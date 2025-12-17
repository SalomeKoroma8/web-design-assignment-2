# SALOME
— Sierra Leone Football Association Website

Welcome to SALOME — a clean, responsive, and content-first website scaffold built for the Sierra Leone Football Association (SLFA). This lightweight static site collects news, fixtures, player information, services, and contact details in a simple set of HTML pages you can open locally or host on any static-file web host.

## What This Project Is

- **Purpose:** Provide an accessible, easy-to-maintain web presence for the SLFA with pages for news, matches, players, services, and contact.
- **Type:** Static HTML site (no build system required).
- **Files of interest:** `index.htm`, `news.htm`, `matches.htm`, `players.htm`, `services.htm`, `contact.htm`.

## Highlights

- Crisp, consistent branding and color variables used inline for quick edits.
- Responsive footer layout using CSS Grid and a sticky/fixed header so navigation is always available.
- A simple contact form layout that can be wired to any backend or form service.
- Minimal, dependency-free code — easy to host on GitHub Pages, Netlify, or any static host.

## Quick Start

1. Clone or copy the project folder to your machine.
2. Open the site locally by double-clicking `index.htm` (or open it in your browser):

```powershell
start "" "c:\Users\PC\Desktop\SALOME\index.htm"
```

3. Edit pages with your favorite editor. All pages are plain HTML with embedded CSS for quick changes.

## Project Structure

- `index.htm` — Home / landing page
- `news.htm` — News and announcements
- `matches.htm` — Fixtures and results
- `players.htm` — Player profiles and roster
- `services.htm` — Programs, development, and services offered
- `contact.htm` — Contact information and form
- `Pictures/` — Static image assets used by the site

## Development Notes

- Accessibility: Add explicit `<label>` elements for form inputs and improve ARIA attributes before production deployment.
- Form handling: The contact form is a front-end scaffold only. Provide a server endpoint or integrate a form service (Formspree, Netlify Forms, etc.) to collect submissions.
- Styling: CSS is embedded for simplicity; consider moving to a separate stylesheet for caching and maintainability.

## Hosting Recommendations

- For small static sites, GitHub Pages or Netlify are excellent free options. Simply push the folder to a repository and configure the static site settings.
- If you need HTTPS, both GitHub Pages and Netlify provide it automatically.

## Contributing

If you plan to extend this site:

- Standardize on a CSS file (move styles out of each HTML file).
- Add a simple build step (optional) if you want templating (Eleventy, Hugo, or Jekyll).
- Keep images optimized (use web-friendly formats and sensible dimensions).

## License

This project contains example files. Add a license file (`LICENSE`) to declare usage permissions. If you're unsure, consider `CC BY-SA` for content and `MIT` for code.

## Author

- **Author:** SALOME Web Team

