# GitHub Pages for resume

This repository contains a single `resume.html` file and an `index.html` redirect so the resume is served from the site root.

How it works:
- `index.html` redirects to `resume.html`.
- GitHub Actions workflow at `.github/workflows/pages.yml` publishes the repository to GitHub Pages on every push to `main`.

After you push to `main`, enable GitHub Pages in the repository settings (if not already enabled) and the site will be available at `https://<your-username>.github.io/<repo-name>/` and will redirect to `resume.html`.

If you want the resume at the repository root without a redirect, move the contents of `resume.html` into `index.html` instead.
