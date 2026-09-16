# Go Go Hankuk Admin Dashboard

A working admin dashboard for Go Go Hankuk, built from the Figma design
("Go Go Hankuk — Admin Dashboard"). Single self-contained `index.html` —
no build step, no dependencies.

Covers: Overview, Appointments (list + detail), News (list + editor),
Banners, and Team Profiles (list + editor), with interactive mock data
(filtering, search, confirm/publish flows, live-updating previews).

## Run it

Just open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Push to GitHub

This folder is already a git repo with one commit. To push it to a new
GitHub repository:

1. Create a new **empty** repository on GitHub (do not initialize it with
   a README, license, or .gitignore).
2. In this folder, run:

```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```
