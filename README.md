# SAMPAO — Official support and privacy website

This public repository contains **only** the SAMPAO support site and privacy policy. The game code is maintained separately in a private repository.

## Website pages

- English homepage: [index.html](index.html)
- English support: [support.html](support.html)
- English privacy policy: [privacy.html](privacy.html)
- Français : [Accueil](fr/index.html), [Assistance](fr/support.html), [Confidentialité](fr/privacy.html)

## How to activate GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then click **Save**.
4. Verify that the HTTPS pages load in an incognito window.

Expected pages once enabled:
- https://abassale.github.io/sampao-site/support.html
- https://abassale.github.io/sampao-site/privacy.html

## Important before publication

This website uses the developer contact email for public player support; check that the address should be made public. The privacy notice describes the October 2026 TestFlight configuration, in which ads and Premium sales are disabled. Review it and update the Apple App Privacy answers whenever SDK behavior, advertisements or in-app purchases change. Apple also requires a privacy link accessible from inside the app.

## Shared App Store support portal — added November 4, 2026

New landing page: `games.html`.

| Game | Support (English) | Privacy (English) | Assistance FR | Confidentialité FR |
| --- | --- | --- | --- | --- |
| PAPERWIND | [Support](paperwind/support.html) | [Privacy](paperwind/privacy.html) | [Assistance](paperwind/fr/support.html) | [Confidentialité](paperwind/fr/privacy.html) |
| BASKABOOM | [Support](baskaboom/support.html) | [Privacy](baskaboom/privacy.html) | [Assistance](baskaboom/fr/support.html) | [Confidentialité](baskaboom/fr/privacy.html) |
| SAMPAO | [Support](support.html) | [Privacy](privacy.html) | [Assistance](fr/support.html) | [Confidentialité](fr/privacy.html) |

When GitHub Pages is enabled and publicly verified, potential URLs to enter in App Store Connect are:

- PAPERWIND Support: `https://abassale.github.io/sampao-site/paperwind/support.html`
- PAPERWIND Privacy: `https://abassale.github.io/sampao-site/paperwind/privacy.html`
- BASKABOOM Support: `https://abassale.github.io/sampao-site/baskaboom/support.html`
- BASKABOOM Privacy: `https://abassale.github.io/sampao-site/baskaboom/privacy.html`

**Important checks before entering these URLs in App Store Connect:**
1. In GitHub repository Settings → Pages, deploy from `main` / `/(root)` (if not already enabled) and verify every URL returns an actual public page over HTTPS.
2. Review the privacy statements against the **exact uploaded iOS builds**, particularly BASKABOOM's monetization (repository V1.0.7 docs describe no ads, with a full-game IAP) and PAPERWIND's data handling. Do not mark unverified disclosures as final.
3. Confirm the public support email address remains appropriate and confirm publisher/legal contact fields and any DSA-trader requirements. Do not invent a postal address.
4. Update App Store Connect separately. Adding web pages to this repository does **not** fill Apple forms or submit an app.
5. When SAMPAO activates real advertising and Premium, update its older beta-specific privacy/support text, and retest native SDK privacy behavior.
