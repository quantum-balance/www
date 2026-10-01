# Quantum Balance Website

Production-ready static landing page for **https://quantumbalance.me/**.

## Included

- Responsive one-page website
- Mobile navigation
- SEO title, description, Open Graph metadata and canonical URL
- GitHub Pages `CNAME`
- `robots.txt`
- `sitemap.xml`
- SVG favicon
- Meyersdal and Kempton Park service information
- WhatsApp booking links
- Practitioner profile for Isabel Swart
- Wellness and medical-claims disclaimer
- Accessibility basics including semantic sections, keyboard-friendly navigation and reduced-motion support

## Deploy to GitHub

Repository:

`https://github.com/quantum-balance/www`

### Option 1 — Upload in GitHub

1. Open the `quantum-balance/www` repository.
2. Choose **Add file → Upload files**.
3. Extract this ZIP locally first.
4. Upload the **contents of the `quantum-balance-www` folder**, not the ZIP itself.
5. Commit to the `main` branch.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select:
   - Branch: `main`
   - Folder: `/ (root)`
9. Save.

Because the package already contains a `CNAME` file, GitHub Pages should use:

`quantumbalance.me`

## DNS

For an apex domain on GitHub Pages, configure the DNS records recommended by GitHub for the current GitHub Pages service. Also add a `www` CNAME if you want `www.quantumbalance.me` to resolve.

After DNS is live, enable **Enforce HTTPS** in GitHub Pages settings.

## Files

- `index.html` — website content
- `styles.css` — responsive visual design
- `script.js` — mobile menu and dynamic copyright year
- `favicon.svg` — lightweight site icon
- `CNAME` — custom domain
- `.nojekyll` — disables Jekyll processing
- `robots.txt` — crawler rules
- `sitemap.xml` — basic search-engine sitemap

## Content note

The Bio Resonance copy is deliberately framed as **complementary wellness**, not as a medical diagnostic or treatment service. This avoids presenting unverified medical claims such as detecting disease, pathogens, deficiencies or hormonal conditions.

Before launch, replace or add:

- Isabel Swart portrait
- Quantum Balance logo, if available
- Exact street addresses if you want them public
- Pricing/session duration
- Privacy Policy / POPIA notice
- Terms or cancellation policy
- Social media profile links

## Local preview

You can simply open `index.html` in a browser. For a proper local server:

```bash
python -m http.server 8080
```

Then visit:

`http://localhost:8080`
