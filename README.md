# Aseema S — Portfolio Website

Responsive animated portfolio made with React, Vite, CSS and Lucide icons.

## Run on Windows
1. Extract `Aseema_Portfolio_Website.zip`.
2. Install Node.js LTS from https://nodejs.org/ if it is not installed.
3. Open the extracted `Aseema_Portfolio_Website` folder in File Explorer.
4. Click the address bar, type `cmd`, press Enter.
5. Run:
   ```bash
   npm install
   npm run dev
   ```
6. Open the URL shown in the terminal, usually `http://localhost:5173`.
7. Stop the server with `Ctrl + C`.

## Build for hosting
```bash
npm run build
```
The finished website is created in `dist/`.

## Free hosting: Vercel
1. Create a GitHub account/repository and upload the project files (do not upload `node_modules`).
2. Sign in at https://vercel.com using GitHub.
3. Choose **Add New → Project**, import your repository, and deploy.
4. Build command: `npm run build`; output directory: `dist` (Vite is usually detected automatically).
5. Vercel provides a public URL. Free-tier limits and terms apply.

## Alternative free hosting: Netlify
1. Run `npm install` and `npm run build` locally.
2. Sign in at https://www.netlify.com/.
3. Use **Add new site → Deploy manually** and drag the `dist` folder into the deploy area, or connect your GitHub repository using build command `npm run build` and publish directory `dist`.

## Edit your content
- Contact email and social links: `src/main.jsx`.
- Project descriptions and tags: the `projects` array near the top of `src/main.jsx`.
- Update project-specific links to point to each real repository when available.
- Check that all project descriptions accurately represent work you have completed; some are written as explorations/concepts.
- Google Fonts and package installation require internet access.
