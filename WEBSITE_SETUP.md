# SNS Rookies iOS — GitHub Pages website

The custom static website is at `index.html`. It does not modify or interfere with the iOS build scripts.

## Publish

1. In the GitHub repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then **Save**. If you prefer publishing from the default branch, merge the website files first and select that branch instead.
4. GitHub Pages will provide the published URL after deployment. The expected project URL format is `https://mradams76.github.io/SNS-Rookies-iOS-Website/`, but confirm in Settings → Pages.

## Content and release management

- The Downloads section reads the repository's latest **published GitHub Release** using GitHub's public API. It shows a direct IPA download link **only when an actual .ipa asset exists**. Drafts and prereleases are not reported as the latest stable release.
- To add authentic screenshots, place optimized images under `assets/` and replace the three screenshot placeholders in `index.html` with accessible `<img>` tags. Only publish captures you approve.
- Replace the provisional credit paragraph with verified original creator/contributor names and source links before promoting the website.
- No analytics, trackers, external JavaScript frameworks, or user accounts are required.
- GitHub Pages is a static host; it cannot sign or install unsigned IPA files. Document your installation requirements in each release.
