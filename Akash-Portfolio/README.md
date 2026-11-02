# Akash Portfolio

A static HTML portfolio website prepared from the supplied HTML export.

## Project contents

- `index.html` — the supplied portfolio HTML, copied without modification.
- `README.md` — this project and deployment guide.
- `.gitignore` — common local/editor/OS files excluded from Git.
- `assets/` — reserved for separate assets if they are added later. The supplied HTML contains its profile image inline, so no image was extracted or replaced.

## Run locally

1. Open the `Akash-Portfolio` folder.
2. Double-click `index.html` to open it in a modern browser.
3. Check the page at desktop and mobile viewport sizes.

The site is a static HTML file and does not require a build step or package installation. An internet connection may be needed for externally hosted resources referenced by the original HTML, such as web fonts.

## Publish to GitHub

1. Create a new empty repository on GitHub (for example, `akash-portfolio`).
2. Open a terminal in this folder.
3. Run the following commands, replacing the URL with the repository URL:

```bash
git init
git add .
git commit -m "Initial commit - Akash Portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/akash-portfolio.git
git push -u origin main
```

## Deploy with GitHub Pages

1. Push this project to GitHub.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then save.
5. Wait for GitHub Pages to publish the site. The entry page is `index.html`.

## Preservation and verification notes

- `index.html` is an unmodified byte-for-byte copy of the supplied HTML attachment.
- No framework conversion, redesign, dependency installation, or CSS/JavaScript rewrite was performed.
- The source HTML includes its embedded profile image; it was kept embedded exactly as supplied.
- The original file references externally hosted resources. Those references were not changed.
- This packaging step verifies file integrity and inspects the HTML source for common structural elements and asset references. It does **not** execute the website in a real browser, so visual appearance, animation timing, responsive behavior, and every interactive path still require manual browser testing on desktop and mobile.
- No separate original source project, original component files, or original asset directory was supplied. This package does not claim to reconstruct them.
- Review public contact details and links with the portfolio owner before publishing.
