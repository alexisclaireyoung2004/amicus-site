# Amicus project website (CS 147, Autumn 2026)

Context for Claude Code when working in this repo.

## What this is
Static project website for Amicus, a peer support app for people navigating court on their own. It is graded under CS 147 Assignment 3 (UX, visual design, content, and completeness of deliverables).

## Hard rules (from the assignment)
- Plain HTML, CSS, and vanilla JS only. No frameworks, no build step.
- **Relative links only.** Never start a path with `/` and never link to our own domain. The site moves from web.stanford.edu to hci.stanford.edu at the end of the term.
- Team names are **first name + last initial** only (e.g. "Nicole N."), everywhere including file contents.
- File names: lowercase, hyphens, no spaces (AFS is case-sensitive).
- Compress images (TinyPNG) and videos (HandBrake, H.264, RF 24) before committing.
- Every video needs three formats: embedded `<video>`, YouTube/Vimeo link, and a download link.
- Hosting is AFS only. Do not suggest GitHub Pages, Netlify, Vercel, Wix, etc.

## Structure
- `index.html`: single page with sections Home, Concept, Process (deliverables A1 to A11), Prototype (videos), Team
- `css/style.css`: brand tokens in `:root` at the top (colors sampled from the logo, Poppins + Nunito)
- `js/main.js`: mobile menu, sticky header, active nav highlighting
- `assets/img/`: logo (`amicus-logo.svg`, transparent), icon, favicon, screenshots, team photos (`assets/img/team/`)
- `deliverables/`: slides, PDFs, READMEs, spreadsheets
- `media/`: compressed video files

## Adding a deliverable
Drop the file in `deliverables/`, update the matching card in the Process section (remove `is-soon`, turn `<span class="link-soon">` into an `<a>` with a relative href).

## Writing style
Concise and error-free. No em dashes.

## Deploy
`./deploy.sh` (see README).
