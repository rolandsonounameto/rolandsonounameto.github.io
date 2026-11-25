# rolandsonounameto.github.io

Personal academic website: plain HTML/CSS, served by GitHub Pages.

## Files
- `index.html`: home (intro, expertise, selected papers, projects)
- `about.html`: bio, interests, experience, education, contact
- `publications.html`: papers, talks and posters, with a type filter
- `writing.html`: articles and peer review
- `assets/style.css`: all styling (colours are at the top)
- `assets/avatar.svg`: placeholder portrait. Replace it with your photo.

Search for `EDIT` and `[...]` to find the text to fill in.

## Publish (first time)
1. On GitHub, create a **public** repository named exactly `rolandsonounameto.github.io`. Don't add a README.
2. In this folder, run:
   ```
   git init
   git add .
   git commit -m "First version of my website"
   git branch -M main
   git remote add origin https://github.com/rolandsonounameto/rolandsonounameto.github.io.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**, set *Source* to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After 1–2 minutes the site is live at https://rolandsonounameto.github.io/

Without git installed, you can drag the files onto the repository page in the browser ("Add file → Upload files").

## Update
Edit the files, then:
```
git add .
git commit -m "Update"
git push
```
