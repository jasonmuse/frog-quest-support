# Frog Quest+ Support Site

Static GitHub Pages site for Frog Quest+ by Jason Muse.

No build tools, frameworks, analytics, tracking scripts, or third-party requests. The site is plain HTML and CSS, plus the same tiny random-sky script as jasonmuse.github.io.

## Look

It matches jasonmuse.github.io: a purple-to-blue background picked on each load, Lato (self-hosted in `fonts/`), the dark rounded panel, and the EarthBound squiggle behind section titles. The Frog Quest touches are the game's own title logo, the frog-green app card, the App Store screenshot reel, and Lil Froggy in his crown hopping in the footer.

## Pages

- `index.html`: home (title art, App Store link, screenshots, links)
- `support.html`: contact plus the FAQ (jumping, saves, unlocks, Endless, Remove Ads/restore, tracking, refunds, iPad/iPhone Duo, troubleshooting)
- `privacy_policy.html`: same text as the in-game `legal/privacy_policy.txt` in the game repo; keep them in sync
- `terms_of_use.html`: same text as the in-game `legal/terms_of_use.txt`
- `styles.css`, `fonts/`, `images/`

## Support requests

"Open a Support Request" goes to this repo's GitHub Issues, with forms in `.github/ISSUE_TEMPLATE/` ("Something's not working" and "Question or idea"). Billing links to Apple's reportaproblem.apple.com. Issues are public, and the forms say so.

## Current GitHub Pages URLs

This repo remote is `jasonmuse/frog-quest-support`, so the expected project Pages URLs are:

- Marketing URL: `https://jasonmuse.github.io/frog-quest-support/`
- Support URL: `https://jasonmuse.github.io/frog-quest-support/support.html`
- Privacy Policy URL: `https://jasonmuse.github.io/frog-quest-support/privacy_policy.html`
- Terms URL: `https://jasonmuse.github.io/frog-quest-support/terms_of_use.html`

If the repo is renamed to `frogquest`, use:

- Marketing URL: `https://jasonmuse.github.io/frogquest/`
- Support URL: `https://jasonmuse.github.io/frogquest/support.html`
- Privacy Policy URL: `https://jasonmuse.github.io/frogquest/privacy_policy.html`
- Terms URL: `https://jasonmuse.github.io/frogquest/terms_of_use.html`

## Enable GitHub Pages

1. Open the repo on GitHub.
2. Go to Settings.
3. Go to Pages.
4. Set Source to `Deploy from a branch`.
5. Set Branch to `main`.
6. Set Folder to `/root`.
7. Save.

## App Store Connect Fields

Use the live GitHub Pages URLs after deployment.

- Support URL: `https://jasonmuse.github.io/frog-quest-support/support.html`
- Marketing URL: `https://jasonmuse.github.io/frog-quest-support/`
- Privacy Policy URL: `https://jasonmuse.github.io/frog-quest-support/privacy_policy.html`
- Copyright: `2026 Jason Muse`

Keep release set to manual for the first launch unless you intentionally want automatic release after approval.

## AdMob app-ads.txt

Do not rely on a project Pages path for AdMob app-ads.txt. For the `jasonmuse.github.io` domain, Google expects this file at the root:

`https://jasonmuse.github.io/app-ads.txt`

Add `app-ads.txt` to the root of the existing `jasonmuse.github.io` portfolio repo with exactly:

```text
google.com, pub-3776793413956253, DIRECT, f08c47fec0942fa0
```

