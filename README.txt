# Little Steps Preschool — Static Website

This folder is ready to upload to GitHub Pages or any static host.

## Folder structure

  static-site/
  ├── index.html          ← Homepage (open this to preview)
  ├── 404.html
  ├── robots.txt
  ├── sitemap.xml
  ├── images/             ← All website images (replace files here later)
  │   ├── hero/
  │   ├── about/
  │   ├── programs/
  │   ├── facilities/
  │   ├── gallery/
  │   └── og/
  └── _next/              ← CSS and JavaScript (do not delete)

## Preview on your computer

IMPORTANT — use one of these (do NOT double-click index.html):

  npm run preview:static
  Then open http://localhost:3000

Or rebuild + preview in one step:

  npm run preview

To edit the site with live reload:

  npm run preview:dev
  Then open http://localhost:3000

## Upload to GitHub Pages (simple method)

1. Create a new GitHub repository
2. Upload ONLY the contents of this static-site folder (not the whole Next.js project)
3. GitHub → Settings → Pages → Deploy from branch → main → / (root)
4. Your site will be at: https://YOUR_USERNAME.github.io/REPO_NAME/

For this project (little-steps-website), rebuild with:

  npm run export:github

Then upload the contents of static-site/ again.

## Replace images later

Drop new photos into the matching subfolder under images/ using the same filename.
Example: replace images/hero/hero-main.svg with hero-main.jpg and update the
source project if the extension changes.

## Contact form

Form uses mailto fallback until Formspree is configured in the source project.
