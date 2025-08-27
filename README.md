This repo contains the single-page portfolio website for VVP Tech, an IT consultancy based in Pune, Maharashtra, India.

Site details:
- Company: VVP Tech
- Proprietor: Mrs. Vasudha Patil
- Location: Pune, Maharashtra, India

Tech choices:
- Minimal static site using semantic HTML
- Styling with Pico.css (CDN) + a small custom stylesheet in `assets/styles.css`
- No build step; compatible with GitHub Pages

Local preview:
Option A — Node (recommended):
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start local server:
   ```bash
   npm start
   ```
3. Visit `http://localhost:3200`.

Node version:
- This repo includes an `.nvmrc` set to `lts/*`. With `nvm` installed:
  ```bash
  nvm use
  # or to install if missing
  nvm install
  ```
- npm will enforce the Node version specified in `package.json` because `.npmrc` sets `engine-strict=true`.

Option B — Open the file directly:
1. Open `index.html` in a browser.

Option C — Python:
1. Serve locally (Python example):
   ```bash
   python -m http.server 8080
   ```
2. Then visit `http://localhost:8080`.

Deploy to GitHub Pages:
1. Push this repository to GitHub.
2. In the repository settings → Pages, set:
   - Source: Deploy from a branch
   - Branch: `main` (root)
3. Save. The site will be available at `https://<your-username>.github.io/<repo-name>/`.

Custom domain (optional):
- Add your domain’s DNS A/AAAA/CNAME per GitHub Pages docs.
- Create a `CNAME` file at the repo root with your domain.

Content updates:
- Edit `index.html` to modify sections or text.
- Update brand colors and spacing in `assets/styles.css`.
