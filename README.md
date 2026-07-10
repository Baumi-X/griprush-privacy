# Baumi-X Website

This repository hosts the public website for **Baumi-X**, an independent
mobile game developer, via GitHub Pages.

Live site: https://baumi-x.github.io/griprush-privacy/

## Structure

- `index.html` – Home page: about Baumi-X and an overview of current
  projects (GripRush).
- `privacy.html` – The canonical GripRush privacy policy (DE/EN), linked
  from the Google Play Store listing.
- `games/griprush.html` – Project page for GripRush (feature overview,
  screenshot placeholders, store link).
- `contact.html` – Contact / legal notice (imprint), email
  `baumix@gmail.com`.
- `styles.css` – Shared dark-theme stylesheet (header/nav, footer, cards)
  used by all pages.

No build tools are used — this is plain static HTML/CSS/JS, fully
compatible with GitHub Pages.

## Google Play Store link

The Google Play Store listing for GripRush links to this domain. Since
`index.html` was previously the privacy policy itself, the policy has been
moved to `privacy.html` and `index.html` is now the site's home page. The
home page prominently links to **"Datenschutzerklärung / Privacy Policy"**
(`privacy.html`), so the privacy policy remains easy to find whether the
Play Store link points at the root domain or is updated to point directly
at `privacy.html`.

The source draft (with editorial history) is maintained in the main
GripRush game repository at `Griprush/PRIVACY_POLICY_DRAFT.md`. When that
draft changes, update `privacy.html` here to match and keep the "Last
updated" date in sync.
