# cprstudios.com

Static marketing + legal site for CPR Studio. Served by **GitHub Pages**.

## Deploy

Anything pushed to `main` deploys automatically:

```bash
git add .
git commit -m "..."
git push
```

## DNS (Squarespace Domains)

The `cprstudios.com` apex resolves to GitHub Pages via these A records:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

And `www.cprstudios.com` is a `CNAME` to `cpr-studios-llc.github.io`.

## Files

- `index.html` — homepage
- `privacy.html` — privacy policy (linked from in-app paywall, settings, App Store Connect)
- `terms.html` — terms of service
- `styles.css` — shared styling
- `CNAME` — tells GitHub Pages which domain to serve

## Note

The privacy policy URL `https://cprstudios.com/privacy.html` is referenced in the Keeply iOS app and App Store Connect metadata. Don't change the filename without updating those.
