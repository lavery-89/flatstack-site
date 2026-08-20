# FlatStack public holding page

Static holding page for **https://flatstack.hk**.

## Files

- `index.html` — page markup, SEO metadata, Open Graph metadata and structured data
- `styles.css` — responsive styling
- `robots.txt` — crawler rules
- `sitemap.xml` — initial sitemap
- `site.webmanifest` — basic web-app metadata
- `assets/favicon.svg` — temporary FlatStack favicon/mark
- `CNAME` — custom domain for GitHub Pages

## GitHub Pages deployment

1. Create a GitHub repository, for example `flatstack-site`.
2. Add these files to the repository root.
3. In GitHub: **Settings → Pages**.
4. Set **Source** to `Deploy from a branch`.
5. Choose the `main` branch and `/ (root)`.
6. GitHub Pages should detect the `CNAME` file and use `flatstack.hk`.
7. In Dynadot DNS, point the domain to GitHub Pages once the registration is active.
8. Back in GitHub Pages, enable **Enforce HTTPS** once the certificate is issued.

## DNS

For an apex/root domain such as `flatstack.hk`, GitHub currently documents a set of A/AAAA records for GitHub Pages. Check GitHub's current Pages documentation before adding them, because infrastructure addresses can change.

You may also add `www.flatstack.hk` as a CNAME to your GitHub Pages hostname and redirect it to the apex domain.

## Before launch

Replace the temporary inline/ favicon mark with the final FlatStack logo if desired.

Optional later additions:

- `og-image.png` (1200×630) for social sharing
- privacy/contact pages
- analytics
- Google Search Console / Bing Webmaster Tools verification
