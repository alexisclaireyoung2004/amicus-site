# Amicus website

Project website for Amicus (CS 147, Autumn 2026).

Live: http://web.stanford.edu/class/cs147/projects/STUDIO_NAME/amicus/ (update once deployed)

## Working on it locally
1. Clone the repo.
2. Preview it by opening `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
3. To make changes with Claude Code, run `claude` in this folder. It reads `CLAUDE.md` for the project rules.

## Adding deliverables
- Files go in `deliverables/` (lowercase, hyphens, no spaces), e.g. `deliverables/a5-lofi-prototyping.pdf`.
- Compressed videos go in `media/`.
- Then update the matching card in the Process section of `index.html`.

## Deploying to AFS
1. Fill in `STUDIO` (and confirm `PROJECT`) at the top of `deploy.sh`.
2. Run `chmod +x deploy.sh` once.
3. Run `./deploy.sh your-sunet-id` and approve the Duo prompt.

`--delete` makes the server match this folder exactly, so always deploy from an up-to-date copy of `main`. Check the course's upload handout if anything about the path or permissions differs.

## Checkpoint (Oct 29-30)
- [ ] Site live at the team URL
- [ ] A1 slides linked
- [ ] A2 slides linked
- [ ] A4 slides and concept video (embedded, YouTube, download)
