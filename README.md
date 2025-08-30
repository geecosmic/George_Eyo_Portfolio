# George E. Eyo — Static Portfolio

This is a single-page, static portfolio (HTML + Tailwind CDN). It doubles as your online CV and a place to host APKs.

## How to Deploy (GitHub Pages)
1. Create a new GitHub repo and push this folder's contents.
2. In the repo settings, enable Pages → Deploy from branch → `main` → `/ (root)`.
3. Your site will be live at `https://<your-username>.github.io/<repo>/`.

## Netlify / Vercel
- Drag and drop this folder into Netlify/Vercel dashboard. No build command needed.

## Add APKs
- Put your `.apk` files in `files/`.
- Update the `projectData` array in `index.html` with the correct paths (e.g., `files/app-v1.apk`).

## Update CV
- Replace `assets/George_Eyos_CV_2025.pdf` with your latest CV file; keep the same name or update the link in `index.html`.
