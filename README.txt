LAUREN REKHELIS PORTFOLIO — GITHUB PAGES

All website files are FLAT: no subfolders required.

1. Create a public GitHub repository (for example, lauren-portfolio).
2. Upload ALL files from this directory into the repository ROOT (not a nested folder).
3. Commit the files.
4. Go to Settings > Pages > Build and deployment.
5. Choose Deploy from a branch, branch main, folder /(root), then Save.
6. Wait for GitHub Pages to publish the site.

The site works without a build step, package manager, or server-side code.
It uses hash routes (#bio, #stem, #plates, #project/...) so internal navigation works on GitHub Pages.

FILES
index.html = entry page
styles.css = layout and responsive styling
app.js = pages, tabs, image carousel, navigation
 data.js = project/photograph metadata
*.jpg = flattened, uniquely named original images resized for web
 automata-project-report.pdf = Lauren's original project report

NOTES BEFORE PUBLISHING
- The technical images are sequenced according to their numbered filenames.
- Where no written step-by-step explanation was supplied, descriptions intentionally avoid inventing technical details.
- The remaining license-plate images have place-based placeholder descriptions, not invented travel anecdotes. Replace them with Lauren's own stories as desired.
- The original files contain different volunteer-hour totals; the website deliberately avoids publishing a disputed number.
- Google Fonts requires an internet connection; system fonts are provided as fallback.
- This is an independently designed student portfolio inspired by broad cinematic scrolling design principles, not a reproduction of Northrop Grumman branding or assets.
