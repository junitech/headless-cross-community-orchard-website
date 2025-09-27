# Copilot Instructions for AI Coding Agents

## Project Overview
This is a static website for the Headless Cross Community Orchard. The codebase is simple and consists of HTML, CSS, and image assets. There is no backend, build system, or dynamic scripting.

## Directory Structure
- `index.html`, `links.html`: Main site pages. All navigation and content are static.
- `style/`: Contains CSS files (`site.css`, `links.css`).
- `media/images/`: Contains image assets used in the site.
- `CNAME`: Used for custom domain configuration (GitHub Pages).
- `README.md`: Project overview (minimal).

## Key Patterns & Conventions
- All site navigation is hardcoded in HTML files. No JavaScript or dynamic routing.
- CSS is split by page/function (e.g., `site.css` for general styles, `links.css` for the links page).
- Images are referenced with relative paths from HTML and CSS.
- No external dependencies, package managers, or build steps.
- No tests or automation scripts are present or required.

## Developer Workflows
- **Preview:** Open HTML files directly in a browser to view changes.
- **Deploy:** Push changes to the `main` branch; site is published via GitHub Pages.
- **Custom Domain:** Managed via the `CNAME` file.

## Integration Points
- **GitHub Pages:** Deployment is automatic from the `main` branch. No additional configuration is needed beyond the `CNAME` file for custom domains.

## Examples
- To add a new image: Place it in `media/images/` and reference it in HTML/CSS.
- To update styles: Edit the relevant CSS file in `style/` and reload the page in your browser.
- To add a new page: Create a new `.html` file and link it from existing pages.

## AI Agent Guidance
- Do not add build tools, package managers, or JavaScript unless explicitly requested.
- Maintain the static, minimal architecture.
- Reference images and styles using relative paths.
- Keep navigation and links hardcoded in HTML.
- Document any new conventions in this file if the project evolves.

---
_Last updated: 2025-09-27_
