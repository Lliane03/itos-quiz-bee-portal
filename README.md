# IT Quiz Bee Portal

Static site (no build step). Files: index.html, manifest.webmanifest, sw.js, icon.svg.

## Deploy on Netlify
1. Go to app.netlify.com, then Add new site, then Deploy manually.
2. Drag this whole folder (or the .zip) onto the page. Done.

## Deploy on GitHub Pages
1. Create a new GitHub repository and upload these files to the root.
2. Settings, then Pages, then Source: Deploy from a branch, branch main, folder / (root).
3. Open https://YOUR-USERNAME.github.io/REPO-NAME/

## Notes
- The service worker makes it work offline and installable, and it needs https (Netlify and GitHub Pages both provide it).
- After you change index.html, change the version in sw.js (quizbee-v1 to quizbee-v2) so visitors get the update.
- Progress is stored in each visitor's own browser.
