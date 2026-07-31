# Khmer Pride Keyboard public pages

Public support, privacy, and terms pages for `ក្តារចុចមោទនភាពខ្មែរ`
(Khmer Pride Keyboard).

## Canonical public URLs

**Use GitHub Pages only.** Do not use `cheng.sokdara.com` for Play Store, Google
OAuth, or in-app links (that custom domain may expire).

| Page | URL |
|------|-----|
| Home | https://chengsokdara.github.io/khmer-pride-keyboard/ |
| Privacy | https://chengsokdara.github.io/khmer-pride-keyboard/privacy-policy/ |
| Terms | https://chengsokdara.github.io/khmer-pride-keyboard/terms-of-service/ |
| Support | chengsokdara@gmail.com |

If github.io redirects to a custom domain, remove the custom domain under  
**GitHub → Settings → Pages → Custom domain** so github.io stays stable.

## Source of truth in the app monorepo

Markdown drafts:

- `khmerlish-keyboard/apps/android/play-store/legal/privacy-policy.md`
- `khmerlish-keyboard/apps/android/play-store/legal/terms-of-service.md`

After changing those drafts, update the HTML here and push to `main`.

## Google OAuth branding verification

1. Put homepage / privacy / terms as the **github.io** URLs above.
2. Authorized domain: `github.io`.
3. Verify ownership in [Google Search Console](https://search.google.com/search-console)
   as `chengsokdara@gmail.com` (HTML meta tag in this repo’s `index.html` is the
   usual path for GitHub Pages).
4. Full checklist: monorepo `docs/GOOGLE_CLOUD_OAUTH_SETUP.md`.

This repository contains only public support material. No internal product
code names in user-facing copy.
