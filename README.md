# Loopivie official website — JLPT Tamani

Minimal, responsive static website for GitHub Pages. No external fonts, trackers, images, frameworks, or build tools.

## Files
- `index.html`: Loopivie homepage
- `privacy/index.html`: JLPT Tamani privacy policy **DRAFT**
- `support/index.html`: help and contact
- `assets/style.css`: responsive design

## REQUIRED BEFORE GOING LIVE
1. Confirm Codex has actually rebranded the user-visible app to **JLPT Tamani**.
2. **Verify the full, actual release build's network requests, analytics, crash reporting, device storage, SDKs, and privacy data**. The privacy page is marked DRAFT because these claims are not fully verified.
3. Update the advertising section immediately if AdMob or any ad/measurement SDK is included. Verify GDPR/EEA/UK consent, ATT if applicable, Apple App Privacy, and Google Play Data Safety.
4. Update privacy policy date and remove the yellow pre-release draft notice **only once the contents are accurate**.
5. Verify that `loopivie.dev@gmail.com` is the public support address you want.
6. Add complete third-party licensing and source attribution separately after completing the repository's `COMMERCIAL_LICENSE_AUDIT.md` blockers. Do not publish an incomplete license page claiming compliance.
7. Update the app's placeholder `http://localhost:3000/privacy` to the real public HTTPS URL once deployed.

## Deploy on GitHub Pages (no custom domain needed)
1. Create a **public** GitHub repository named e.g. `loopivie-site`. Keep the app's private source code and secrets OUT of this repo.
2. Upload the website files at the repository ROOT, not the outer folder in the ZIP.
3. In repository **Settings > Pages > Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
4. Public URLs will usually be:
   - `https://YOUR_GITHUB_USERNAME.github.io/loopivie-site/`
   - `https://YOUR_GITHUB_USERNAME.github.io/loopivie-site/privacy/`
   - `https://YOUR_GITHUB_USERNAME.github.io/loopivie-site/support/`
5. Only after verifying the live URL should you replace the app privacy placeholder and enter the App Store Connect/Google Play URLs.

These are example URL patterns, not existing links.

## Preview locally
Open `index.html` in a web browser. The site uses only relative links.
