# Mirum Q2 vs Q3 2026 filing check

Static dashboard (single index.html). No build step.

## Publish on GitHub Pages
1. Create a new public repository on GitHub (e.g. mirum-q3-2026).
2. Add file > Upload files > drag in index.html and og-image.png > Commit.
3. Settings > Pages > Source: "Deploy from a branch" > Branch: main, folder: / (root) > Save.
4. After about a minute the page is live at https://<your-username>.github.io/<repo-name>/

## LinkedIn preview image
LinkedIn needs a full URL for the preview image. After the site is live, edit index.html and change
  <meta property="og:image" content="og-image.png">
to
  <meta property="og:image" content="https://<your-username>.github.io/<repo-name>/og-image.png">
Then paste the page URL into https://www.linkedin.com/post-inspector/ to refresh the preview.
