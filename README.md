# Patient App (Final)

This is the final single-folder static patient-tracker app. To run locally, unzip and open `index.html` in your browser.

## Files
- `index.html`, `add.html`, `patient.html` — main app pages (single-page JS + localStorage).
- `investigations/index.html` — vertical investigations table (date columns).
- `assets/logo.png` — hospital logo (ensure visible).
- `assets/pavithra.docx`, `assets/Investigations Chart.pdf` — uploaded templates (if present).
- `README.txt` — usage notes.

## How to upload to GitHub (quick)
1. Create a new repository on GitHub (e.g. `patient-app`). Do **not** add a README (we'll push our files).
2. On your machine, unzip this folder into a local directory.
3. From that directory run:
```bash
git init
git add .
git commit -m "Initial commit - patient app"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
4. In GitHub → Settings → Pages: set source to `main` branch and folder `/ (root)`. Save. Your site will be at `https://<your-username>.github.io/<repo-name>/`

## If GitHub Pages build fails
- Remove any `CNAME` file or custom domain setting (Settings → Pages → Custom domain). The app is static and needs `index.html` at root.
- Make sure no workflow is blocking the Pages build; you can disable Pages Actions if needed.

