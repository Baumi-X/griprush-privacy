# Baumix – Developer Website

This repository hosts the public developer website for **Baumix**, used as
the "developer website" entry in the Google Play Console. It is served via
GitHub Pages.

Live site: https://baumi-x.github.io

## Structure

- `index.html` – Landing page: short bilingual (DE/EN) introduction to
  Baumix and the upcoming game **GripRush** (neon cyberpunk endless
  runner, currently "coming soon" – no store link yet), contact email, and
  a link to the privacy policy.
- `privacy.html` – The canonical GripRush privacy policy (DE/EN), content
  unchanged from the previous single-page version. Linked from the Google
  Play Store listing.
- `impressum.html` – Bilingual (DE/EN) legal notice / imprint (Austrian
  § 5 ECG), with the responsible person's name/address, link disclaimer,
  and EU ODR dispute-resolution notice. Not linked from the homepage
  content, only via the shared nav/footer.
- `styles.css` – Shared dark-theme stylesheet (header/nav, language
  switch, footer) used by all pages.
- `assets/dev-header.jpg` – Optimized hero/header banner shown at the top
  of the landing page (Baumix "BX" logo + "BAUMIX / GAME STUDIO" on a neon
  cyan/magenta grid background). Resized from the 4096×2304 source asset
  (maintained in the main GripRush repo) to 1920px width and re-compressed
  as JPEG (~58 KB) for fast page loads.

All pages use the same DE/EN language-switch mechanism (hash-based
section toggling), matching colors/fonts (`#0b0f14` background, `#e8ecf1`
text, `#22d3ee` → `#d946ef` accent gradient).

No build tools are used — this is plain static HTML/CSS, fully compatible
with GitHub Pages (deploys automatically from `main`).

This repository is named `Baumi-X.github.io`, the special GitHub Pages
user/organization root repo name, so the site is served directly at the
apex domain `https://baumi-x.github.io` (no path suffix).

## Google Play

- **Developer website** (Play Console): the site root,
  https://baumi-x.github.io
- **Privacy policy** (Play Store listing): `privacy.html`,
  https://baumi-x.github.io/privacy.html

The source draft of the privacy policy (with editorial history) is
maintained in the main GripRush game repository at
`Griprush/PRIVACY_POLICY_DRAFT.md`. When that draft changes, update
`privacy.html` here to match and keep the "Last updated" date in sync.

