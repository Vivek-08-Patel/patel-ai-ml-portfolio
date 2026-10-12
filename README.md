# PATEL — AI/ML Portfolio

A futuristic, responsive React portfolio built with Vite and Lucide icons. Includes responsive navigation, project-category filters, project cards, skills, timeline, and contact links.

## Requirements
- Node.js 20.19+ or 22.12+ recommended (current Vite versions require a modern Node release)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL Vite prints in your terminal.

## Production build
```bash
npm run build
npm run preview
```
The deployable static site is created in `dist/`.

## Free deployment with Vercel
1. Create a GitHub repository, for example `patel-ai-ml-portfolio`.
2. Extract this ZIP and open the folder in VS Code.
3. In the terminal, run `npm install`, then `npm run dev` and test the website.
4. Commit and push the project to GitHub.
5. Sign in to Vercel with GitHub and choose **Add New → Project**.
6. Import the repository. Vercel should detect Vite automatically.
7. Confirm Build Command `npm run build` and Output Directory `dist`, then deploy.
8. Each push to the connected branch can trigger a redeployment.

## Before sharing with recruiters
- Replace `PATEL` if you want your full professional name displayed.
- Update `mailto:your.email@example.com` with your real public-facing email.
- Replace the generic GitHub and LinkedIn links with your own profile URLs.
- In `src/main.jsx`, each project card is currently a portfolio concept. Link only real repositories and add real metrics/screenshots after you have run the project.
- Add your resume PDF to `public/` and link it from the hero or navigation if desired.
- Keep only skills you can confidently discuss in an interview.

## Structure
```text
patel-portfolio/
├── index.html
├── package.json
├── README.md
└── src/
    ├── main.jsx
    └── style.css
```
