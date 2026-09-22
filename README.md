# Ananda Manifest & Affirmation — Website

Static marketing + legal site for the Ananda Manifest & Affirmation app: homepage, Privacy Policy, and Terms of Use.
Published via GitHub Pages.

## Structure

- `index.html` — homepage with Play Store / App Store links
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Use (includes subscription & refund policy)
- `assets/` — shared stylesheet, app icon, favicon

## Before publishing — placeholders to replace

- **Store links** in `index.html` (`#playstore`, `#appstore`) — swap for the live App Store / Google Play listing URLs once published.
- **Support email** in `privacy.html` and `terms.html` (`PLACEHOLDER_SUPPORT_EMAIL@example.com`) — replace with the real support/contact address.
- **Governing law jurisdiction** in `terms.html` (`[PLACEHOLDER: your country/state...]`) — replace with the actual jurisdiction.

## Enabling GitHub Pages

1. Push this repo to GitHub as a **public** repo (e.g. `anandapositivity/ananda-app-web`).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)`. Save.
5. The site will be live at `https://<org>.github.io/<repo-name>/` within a minute or two.

## Linked from the app

The Ananda Manifest & Affirmation app's Settings screen (`src/screens/SettingsScreen.tsx` in the `ananda-app` repo) links directly to
`privacy.html` and `terms.html` on this site's published URL — update those constants there if this repo or
domain ever changes.
