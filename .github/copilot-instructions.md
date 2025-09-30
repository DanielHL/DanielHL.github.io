# Copilot Instructions for DanielHL.github.io

## Project Overview
This is a personal academic website, primarily static, with HTML, images, PDFs, and a small set of JavaScript utilities. There is no build system, backend, or package management. All content is served as static files.

## Key Directories and Files
- `index.html`: Main entry point and homepage. Contains the primary site structure and references to scripts and images.
- `js/`: Contains JavaScript libraries and plugins (e.g., `jquery-1.11.2.js`, `imagesloaded.pkgd.js`, `jquery.qtip.js`). No custom JS modules detected.
- Image and PDF files are in the root directory for direct linking.

## Development Workflow
- **Edit HTML directly**: All content and structure changes are made in `index.html` or by adding new static files.
- **No build step**: Changes are reflected immediately. No compilation or bundling is required.
- **No tests or CI/CD**: There are no automated tests or deployment scripts.
- **Preview locally**: Open `index.html` in a browser to preview changes.

## Project Conventions
- Use relative paths for all links to images, PDFs, and JS files.
- Keep all static assets (images, PDFs) in the root directory for simplicity.
- Use only the provided JS libraries; do not add new dependencies unless absolutely necessary.
- Maintain a clean and minimal HTML structure for easy manual editing.

## Examples
- To add a new PDF, place it in the root and link from `index.html`:
  ```html
  <a href="new_paper.pdf">Download my new paper</a>
  ```
- To use a JS plugin, reference it from the `js/` directory:
  ```html
  <script src="js/jquery.qtip.js"></script>
  ```

## AI Agent Guidance
- Do not introduce frameworks, build tools, or package managers.
- Do not restructure the project into subfolders unless explicitly requested.
- Focus on clarity and minimalism in all code changes.
- When adding new content, update `index.html` and place assets in the root or `js/` as appropriate.

---
_Last updated: 2025-09-30_
