# Instructions for My_Website

## Project Overview
This is a static website project consisting of:
- `Index.html`: Main HTML file, entry point for the site
- `style.css`: Central stylesheet for all pages
- `images/`: Directory for image assets

## Architecture & Patterns
- All content is rendered client-side; there is no backend or dynamic scripting.
- The HTML file is structured with semantic elements (e.g., `<header>`, `<main>`, `<footer>`). Maintain this structure for accessibility and SEO.
- CSS is kept in a single file (`style.css`). Add new styles here unless refactoring for scale.
- Images are referenced via relative paths from the `images/` directory.

## Developer Workflows
- No build process or package management is present; changes are made directly to source files.
- Preview changes by opening `Index.html` in a browser. No local server required.
- Debug by using browser developer tools (Inspect Element, Console, Network).

## Project-Specific Conventions
- Use descriptive class and id names in HTML and CSS (e.g., `.hero-section`, `#main-nav`).
- Keep all styling in `style.css`; do not use inline styles unless absolutely necessary.
- Place all new images in the `images/` directory and reference them with relative paths.
- Maintain consistent indentation (2 spaces) and lowercase naming for files and folders.

## Integration Points
- No external dependencies or frameworks are used.
- If adding third-party assets (fonts, icons), document the source and usage in comments within `Index.html`.

## Examples
- To add a new section:
  1. Edit `Index.html` with a semantic element (e.g., `<section class="about">`)
  2. Add styles in `style.css` (e.g., `.about { ... }`)
  3. Place images in `images/` and reference as `<img src="images/about.jpg">`

## Key Files
- `Index.html`: Main structure and content
- `style.css`: All styles
- `images/`: All image assets

---
For questions about conventions or missing documentation, ask the user for clarification before making assumptions.
