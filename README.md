# Nibir's Personal Website

A super-simple personal site built with static HTML/CSS. No build tools or frameworks.

## Files
- `index.html` — main page
- `styles.css` — optional extra styles (currently minimal)
- `resume.pdf` — put your PDF here to enable the Download CV button

## How to Use
1. Replace `resume.pdf` with your actual resume (rename it to `resume.pdf`).
2. Edit text inside `index.html` as needed.

## Free Hosting Options

### Option A: GitHub Pages (no ads, free)
1. Create a new GitHub repository for this site.
2. Upload `index.html`, `styles.css`, and `resume.pdf` to the repository root.
3. In **Settings → Pages**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (root)
4. Save and wait a few moments. Your site will appear at `https://<your-username>.github.io/<repo-name>/`.

**Pro Tip:** If you name the repo `<your-username>.github.io`, the site will be hosted at `https://<your-username>.github.io/`.

### Preparing this repo for GitHub Pages
- Keep `index.html` at the repository root.
- Ensure `styles.css` is present and referenced from `index.html`.
- Add `resume.pdf` if you want the CV download button to work.
- If you want a custom domain later, add a `CNAME` file with the domain name in it.

### Option B: Netlify (drop & deploy)
1. Go to https://app.netlify.com/drop and drag the folder onto the page.
2. Netlify will deploy instantly and give you a public URL (you can customize the subdomain).

### Option C: Cloudflare Pages
1. Create a new project from your GitHub repo.
2. Choose the repo with this site, and deploy. No build steps needed.

## Local Preview
Open `index.html` in any browser by double-clicking it.

## Dark Mode
Click the "🌓 Theme" button to toggle light/dark. The preference is saved in your browser.
