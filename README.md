# EverSince Support

Static GitHub Pages support site for EverSince.

## Files

- `index.html` - Support homepage with contact information, common tasks,
  local-first notes, offline behavior, and troubleshooting.
- `privacy.html` - Privacy policy for first App Store submission with no
  analytics, no ads, no third-party SDKs, and no custom backend.
- `styles.css` - Shared visual styling.
- `assets/` - App icon, favicon PNG, Apple touch icon, and iOS app preview
  image.
- `favicon.ico` - Root browser favicon for clients that request `/favicon.ico`.

## Support Contact

The site uses `contact@absessive.com` for support and privacy questions.

## GitHub Pages Setup

This site is static and deployable from the repository root.

1. Create a new GitHub repository for the support site, or use an existing
   GitHub Pages repository.
2. Copy `index.html`, `privacy.html`, `styles.css`, `favicon.ico`, `assets/`,
   and this `README.md` into the repository root.
3. Commit and push the files.
4. In GitHub, open the repository settings.
5. Go to **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the branch to publish, usually `main`.
8. Select `/ (root)` as the publishing folder.
9. Save the settings.

GitHub Pages will publish the site after the first deployment completes. Use the
published `privacy.html` URL in App Store Connect for the app privacy policy.

## Local Preview

Open `index.html` directly in a browser, or run a local static server from this
directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
