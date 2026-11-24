# Tekon Inverso website

Responsive single-page static website for GitHub Pages.

## Before publishing
- Replace `YOUR_PUBLIC_EMAIL` in `index.html` with a public business email address you want visitors to use.
- Confirm the address and Udyam number shown in the footer before publishing.
- The site currently links no contact form or backend; the contact button opens the visitor's email application.

## Publish
1. Create a public GitHub repository, e.g. `tekon-inverso-website`.
2. Upload `index.html`, `styles.css`, and `script.js` to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for the deployment and open the published GitHub Pages URL.

## Custom domain
1. In **Settings → Pages → Custom domain**, enter the exact domain you own.
2. At your registrar, configure DNS using GitHub's current guide:
   https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
3. For `www`, GitHub generally uses a CNAME to `YOUR-GITHUB-USERNAME.github.io`. For an apex/root domain, use the A records specified in GitHub's guide.
4. Do not remove existing MX records or other DNS records used by email.
5. After DNS propagation, enable **Enforce HTTPS** in GitHub Pages settings.

No build step or backend is required. The hero graphic is CSS-generated. Google Fonts are optional and have system fallbacks.

The website describes an independent R&D enterprise; it does not claim laboratory accreditation or government endorsement.
