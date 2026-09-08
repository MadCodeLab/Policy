# MadCodeLab Policy Pages

Official static privacy policies, terms of service, and app-ads.txt publisher declarations for applications developed by **MadCodeLab**.

## Public URLs (GitHub Pages)

- **Portal Home**: `https://madcodelab.github.io/Policy/`
- **Voice Zoo (ZooVoice)**:
  - Privacy Policy (English - Recommended for Store Review): `https://madcodelab.github.io/Policy/privacy/zoovoice.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/zoovoice-vi.html`
  - Terms of Service: `https://madcodelab.github.io/Policy/terms/zoovoice.html`
- **AdMob app-ads.txt**: `https://madcodelab.github.io/Policy/app-ads.txt`

## Deployment via GitHub Pages

1. Navigate to the repository settings on GitHub: `https://github.com/MadCodeLab/Policy/settings/pages`.
2. Under **Build and deployment** → **Source**: Select **Deploy from a branch**.
3. Under **Branch**: Select `main` and folder `/ (root)`.
4. Click **Save**. The website will be live at `https://madcodelab.github.io/Policy/`.

> `.nojekyll` is included at the repository root to bypass Jekyll processing and ensure all static assets are served verbatim.

## Google Play & Apple App Store Checklist

### Google Play Console
- **Privacy Policy URL**: Fill with `https://madcodelab.github.io/Policy/privacy/zoovoice.html`.
- **In-App Link**: Ensure the same URL is accessible via the app settings or about screen.
- **Developer Name**: Must align with `MadCodeLab`.
- **Data Safety Form**:
  - Personal Information: None collected.
  - Audio / Microphone: Used strictly on-device for gameplay (No data collected or stored remotely).
  - Photos / Media: Coloring book drawings stored in local app memory only.
  - Google AdMob: Technical device IDs and diagnostics handled with child-directed treatment (Rating G, no behavioral profiling).
- **Target Audience**: Families and Children under 13.

### Apple App Store Connect
- **Privacy Policy URL**: `https://madcodelab.github.io/Policy/privacy/zoovoice.html`.
- **App Privacy Questionnaire**: All data handled is not linked to user identity; no tracking across third-party apps.
- **Kids Category (Guideline 1.3 & 5.1.4)**: Parental Gate is active on all outgoing actions and settings; ads are contextual and strictly G-rated.

## AdMob Verification
`app-ads.txt` contains:
```text
google.com, pub-1133420470079320, DIRECT, f08c47fec0942fa0
```
For crawler verification, ensure the domain listed in your Google Play Store / App Store listing points to or redirects to this verified root file.
