# MadCodeLab Policy Pages

Official static privacy policies, terms of service, and app-ads.txt publisher declarations for applications developed by **MadCodeLab**.

## Public URLs

- **Portal Home**: `https://madcodelab.github.io/Policy/`
- **Voice Zoo (ZooVoice)**:
  - Privacy Policy (English - Recommended for Store Review): `https://madcodelab.github.io/Policy/privacy/zoovoice.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/zoovoice-vi.html`
  - Terms of Service: `https://madcodelab.github.io/Policy/terms/zoovoice.html`
- **Puzzlify**:
  - Privacy Policy (English): `https://madcodelab.github.io/Policy/privacy/puzzlify.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/puzzlify-vi.html`
  - Terms of Service: `https://madcodelab.github.io/Policy/terms/puzzlify.html`
- **MadGame**:
  - Privacy Policy (English): `https://madcodelab.github.io/Policy/privacy/madgame.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/madgame-vi.html`
  - Terms of Service: `https://madcodelab.github.io/Policy/terms/madgame.html`
- **HeyStranger**:
  - Privacy Policy (English - Recommended for Store Review): `https://madcodelab.github.io/Policy/privacy/heystranger.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/heystranger-vi.html`
  - Terms of Service (English): `https://madcodelab.github.io/Policy/terms/heystranger.html`
  - Terms of Service (Tiếng Việt): `https://madcodelab.github.io/Policy/terms/heystranger-vi.html`
- **Magic Instrument**:
  - Privacy Policy (English): `https://madcodelab.github.io/Policy/privacy/magicinstrument.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/magicinstrument-vi.html`
  - Terms of Service (English): `https://madcodelab.github.io/Policy/terms/magicinstrument.html`
  - Terms of Service (Tiếng Việt): `https://madcodelab.github.io/Policy/terms/magicinstrument-vi.html`
- **Strongest Character**:
  - Privacy Policy (English - Recommended for Store Review): `https://madcodelab.github.io/Policy/privacy/strongestcharacter.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/strongestcharacter-vi.html`
  - Terms of Service (English): `https://madcodelab.github.io/Policy/terms/strongestcharacter.html`
  - Terms of Service (Tiếng Việt): `https://madcodelab.github.io/Policy/terms/strongestcharacter-vi.html`
- **MadMonsters** (`com.h2qglobal.madmonsters`):
  - Privacy Policy (English - Recommended for Store Review): `https://madcodelab.github.io/Policy/privacy/madmonsters.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/madmonsters-vi.html`
  - Account & Data Deletion Portal (English - Google Play Data Safety URL): `https://madcodelab.github.io/Policy/privacy/madmonsters-delete-account.html`
  - Account & Data Deletion Portal (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/madmonsters-delete-account-vi.html`
  - Terms of Service & EULA (English): `https://madcodelab.github.io/Policy/terms/madmonsters.html`
  - Terms of Service & EULA (Tiếng Việt): `https://madcodelab.github.io/Policy/terms/madmonsters-vi.html`
- **BoostBeat** (`com.h2qglobal.boostbeat`):
  - Privacy Policy (English): `https://madcodelab.github.io/Policy/privacy/boostbeat.html`
  - Privacy Policy (Tiếng Việt): `https://madcodelab.github.io/Policy/privacy/boostbeat-vi.html`
  - Terms of Service (English): `https://madcodelab.github.io/Policy/terms/boostbeat.html`
  - Terms of Service (Tiếng Việt): `https://madcodelab.github.io/Policy/terms/boostbeat-vi.html`
- [AdMob app-ads.txt for all apps](https://h2qglobal.com/app-ads.txt)

## Deployment via GitHub Pages

GitHub Pages for `MadCodeLab/Policy` serves directly from the **`gh-pages`** branch at `/ (root)`.

After committing changes on `main`, merge `main` into `gh-pages` and push both branches so GitHub Pages publishes immediately:

```bash
git push origin main
git checkout gh-pages && git merge main --no-edit && git push origin gh-pages && git checkout main
```

> `.nojekyll` is included at the repository root to bypass Jekyll processing and ensure all static assets are served verbatim.

## Google Play & Apple App Store Checklist

### Voice Zoo (ZooVoice) on Google Play
- **Privacy Policy URL**: Fill with `https://madcodelab.github.io/Policy/privacy/zoovoice.html`.
- **In-App Link**: Ensure the same URL is accessible via the app settings or about screen.
- **Developer Name**: Must align with `MadCodeLab`.
- **Data Safety Form**:
  - Personal Information: None collected.
  - Audio / Microphone: Used strictly on-device for gameplay (No data collected or stored remotely).
  - Photos / Media: Coloring book drawings stored in local app memory only.
  - Google AdMob: Technical device IDs and diagnostics handled with child-directed treatment (Rating G, no behavioral profiling).
- **Target Audience**: Families and Children under 13.

### Voice Zoo (ZooVoice) on the App Store
- **Privacy Policy URL**: `https://madcodelab.github.io/Policy/privacy/zoovoice.html`.
- **App Privacy Questionnaire**: All data handled is not linked to user identity; no tracking across third-party apps.
- **Kids Category (Guideline 1.3 & 5.1.4)**: Parental Gate is active on all outgoing actions and settings; ads are contextual and strictly G-rated.

### MadMonsters (`com.h2qglobal.madmonsters` — 12+ / Teen Online RPG)
- **Google Play Store & Apple App Store Privacy Policy URL**: `https://madcodelab.github.io/Policy/privacy/madmonsters.html`
- **Google Play Data Safety — Delete Account URL**: `https://madcodelab.github.io/Policy/privacy/madmonsters-delete-account.html`
- **Terms of Service & EULA URL**: `https://madcodelab.github.io/Policy/terms/madmonsters.html`
- **Data Safety / App Privacy Declarations**:
  - **Personal Info**: Email address, Trainer Display Name, and internal User ID collected for App Functionality & Account Management (encrypted in transit via TLS 1.3, not shared with third parties, user-deletable).
  - **App Activity / Gameplay Progress**: Monster roster, inventory, Arena/Boss/Guild progress stored on authoritative servers (`api-madmonsters.madcodelab.cloud`).
  - **Financial Info (If IAP Enabled)**: Purchase history / SKU receipt tokens only (payment cards handled solely by Google Play Billing / Apple StoreKit).
  - **Permissions & Tracking**: `INTERNET` only; zero Camera/Microphone/Location/Contacts permissions; zero behavioral ad tracking (no IDFA/GAID cross-app tracking).

### BoostBeat (`com.h2qglobal.boostbeat`)

- Use `https://madcodelab.github.io/Policy/privacy/boostbeat.html` as the Privacy Policy URL in App Store Connect and Play Console. Link to it from the game's settings or about screen. [Apple App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/#privacy) · [Google Play User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311)
- BoostBeat saves progress and settings on the device and supports play without a game account. Complete App Privacy and Data safety for the submitted build on each platform. For builds with ads or purchases enabled, check the bundled SDKs, privacy and consent settings, and purchase information the game receives. [Apple App Privacy Details](https://developer.apple.com/app-store/app-privacy-details/) · [AdMob disclosure for iOS](https://developers.google.com/admob/ios/privacy/data-disclosure) · [AdMob disclosure for Android](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- The publisher ID for BoostBeat's iOS AdMob configuration is `pub-5132455808960555`. [Shared app-ads.txt](https://h2qglobal.com/app-ads.txt)

## AdMob Verification

Use `https://h2qglobal.com` as the developer website in the store listing for apps that use the shared declaration. AdMob looks for the file at the root of the developer website hostname. [AdMob app-ads.txt setup](https://support.google.com/admob/answer/9363762)

The repository's `app-ads.txt` lists the publisher entries for the shared declaration.

```text
google.com, pub-1133420470079320, DIRECT, f08c47fec0942fa0
google.com, pub-5132455808960555, DIRECT, f08c47fec0942fa0
```
