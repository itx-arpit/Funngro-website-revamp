# Funngro Website Revamp

Static 2-page demo website (Home + Teen) for the "Funngro Webpage" — connects teenagers with real company projects so they can learn, earn, and build practical experience.

Site content:
- index.html — Home page (SEO-friendly)
- teen.html — Teen page (step-by-step flow & sign-up demo)
- styles.css — Shared stylesheet
- sitemap.xml — Sitemap referencing both pages
- robots.txt — robots instructions (points to sitemap)
- LICENSE — MIT

Domain placeholder used in files: https://arpitskills-funngro.example/

Quick start (create & push repo manually)
1. Create a new repository on GitHub named `funngro-website-revamp` (public).
2. In your project folder:
   - git init
   - git add .
   - git commit -m "Initial commit — Funngro Website Revamp"
   - git remote add origin https://github.com/itx-arpit/funngro-website-revamp.git
   - git branch -M main
   - git push -u origin main

Deploy:
- GitHub Pages: enable Pages in repo settings (use main branch, /root).
- Netlify: drag & drop the site folder or connect the GitHub repo and enable the site. Netlify Forms is already configured on teen.html.

Notes:
- Replace the placeholder domain (https://arpitskills-funngro.example/) with your real domain once ready.
- Netlify: the form named `funngro-signup` will capture submissions automatically after deploy.