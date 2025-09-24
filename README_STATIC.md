Static site (HTML/CSS/JS) extracted from the Flutter project

How to run locally
- Open index.html directly in your browser, or
- Serve this folder with any static server (for example, using VS Code Live Server or `python -m http.server` from this directory).

Structure
- index.html: Home page (hero, link to EasyChair)
- committees.html: Committees page with chairs and lists
- speakers.html, topics.html, submission.html, venue.html: placeholders to be filled from Flutter pages
- styles.css: shared styles
- main.js: renders shared header and footer

Assets
- This site references images from the existing ../assets/ directory. Keep the relative structure intact when deploying.

Deployment
- Copy the entire web_static/ and the assets/ folder to your hosting. Ensure relative paths remain the same (web_static next to assets).
