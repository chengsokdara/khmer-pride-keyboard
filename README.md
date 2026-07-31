# Khmer Pride Keyboard public pages

Public support, privacy, and terms pages for `ក្តារចុចមោទនភាពខ្មែរ`
(Khmer Pride Keyboard).

## Live URLs

GitHub Pages may redirect to the custom host. Prefer the custom domain in store
and OAuth forms when both work:

| Page | URL |
|------|-----|
| Home | https://cheng.sokdara.com/khmer-pride-keyboard/ |
| Privacy | https://cheng.sokdara.com/khmer-pride-keyboard/privacy-policy/ |
| Terms | https://cheng.sokdara.com/khmer-pride-keyboard/terms-of-service/ |
| Support | chengsokdara@gmail.com |

GitHub Pages fallback host:

- https://chengsokdara.github.io/khmer-pride-keyboard/

## Source of truth in the app monorepo

Markdown drafts used when editing legal copy:

- `khmerlish-keyboard/apps/android/play-store/legal/privacy-policy.md`
- `khmerlish-keyboard/apps/android/play-store/legal/terms-of-service.md`

After changing those drafts, update the HTML in this repo and push to `main`
so GitHub Pages rebuilds.

## Google OAuth branding verification

If Google asks you to verify domain ownership for the app logo / homepage:

1. Use authorized domain **`cheng.sokdara.com`** (custom host) or
   **`chengsokdara.github.io`** (GitHub host).
2. Verify that domain in [Google Search Console](https://search.google.com/search-console)
   with the same Google account that owns the Cloud OAuth project
   (`chengsokdara@gmail.com`).
3. HTML meta tag method: paste the tag Google gives you into `index.html`
   `<head>`, push to `main`, wait for Pages deploy, then click Verify.
4. DNS method (stronger): add the TXT record Google shows on the domain DNS
   for `sokdara.com` / `cheng.sokdara.com` if you control DNS.

Full checklist: monorepo `docs/GOOGLE_CLOUD_OAUTH_SETUP.md`.

This repository contains only public support material. No internal product
code names in user-facing copy.
