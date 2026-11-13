# 1Password Guides GitHub Pages Website

This package contains 800 HTML article pages plus index.html, support.html, style.css, robots.txt and an article index.

## Publish on GitHub Pages

1. Create a GitHub repository. For a user site, name it `YOURUSERNAME.github.io`; for a project site, use any repository name.
2. Upload the extracted files and the `articles` folder to the repository root.
3. Open Settings > Pages, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. Open the Pages URL after deployment.

The styles and links are root relative, designed for a user site at `https://YOURUSERNAME.github.io/`. For a project site at `https://YOURUSERNAME.github.io/REPO/`, change root relative `/style.css`, `/support.html` and `/` links to use the repository prefix before publishing.

The homepage intentionally contains no article listing. Article links are available in `article_urls.txt`, with paths relative to the website root.

The site is independent and not affiliated with 1Password. Existing article CTA links point to third party websites, not verified official 1Password websites.
