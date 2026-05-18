# Privacy Policy for Insignia (Android)

**Last updated:** May 18, 2026  
**App version:** 1.5.3 (see the [Google Play](https://play.google.com) listing for the build you installed)

**Platform:** Insignia is distributed **only on Android** via Google Play. This policy applies to the Android app.

## Introduction

Insignia (“the app”) is an educational app about Swiss military ranks, branches, functions, and insignia. This Privacy Policy explains **what data the app handles**, **what stays on your device**, and **which third parties may process data** when you use features such as advertising or in-app purchases on Android.

**Developer / data controller:** Janis Ringli (individual developer of Insignia).  
We do **not** operate our own user accounts, login servers, or analytics backend for this app.

## Summary (plain language)

| Topic | What happens |
|--------|----------------|
| **Our own servers** | We do **not** collect or store your personal data on servers we run. |
| **On your device** | Language, quiz settings, ad-free status, ad progress, and optional “Support Squad” progress are saved **locally** on your phone or tablet (see below). |
| **Advertising** | **Google AdMob** may show ads and process data (e.g. Android Advertising ID) under [Google’s policies](https://policies.google.com/privacy). |
| **Purchases** | **Google Play** processes payments and related data when you buy or restore “ad-free.” |
| **Offline use** | Browsing insignia and quizzes works **offline**; **ads and Play Store purchases need an internet connection**. |

---

## 1. Data we store on your device (not sent to us)

The app uses Android **SharedPreferences** (via Flutter’s `shared_preferences` package). This information is stored **only on your device** and is **not transmitted to the developer’s servers**:

| Stored item | Purpose |
|-------------|---------|
| **Selected language** | Remember German, French, Italian, or English. |
| **Quiz difficulty** | Remember your quiz mode preference (e.g. free text). |
| **Ad-free unlocked** | Remember whether you unlocked ad-free (purchase or rewarded ads). |
| **Rewarded ad progress** | Count how many rewarded ads you watched toward unlocking ad-free (default target: 10). |
| **Optional support ad count** | Count voluntary “support” rewarded ads after you are ad-free (used only for **Support Squad** rank display—gamification, not a real military status). |
| **“Don’t show again” for ad-free prompt** | Remember if you dismissed the post-quiz suggestion to go ad-free in Settings. |

**Quiz session data** (current score, questions in progress) lives in app memory during a quiz and is not uploaded by us.

**Deleting local data:** Uninstall the app or clear **Insignia** storage under **Settings → Apps** on your Android device.

---

## 2. Data we do **not** collect ourselves

We do **not** intentionally collect or store on our own systems:

- Name, email, phone number, or postal address  
- User accounts or passwords  
- Precise GPS location  
- Photos, microphone, or contacts  
- Your quiz answers as a personal profile on our servers  

We also do **not** use our own crash reporting, product analytics, or marketing email tools in the app.

---

## 3. Third-party services (important)

When you use certain features, **third parties** may collect and process information according to **their** privacy policies. We do not control that processing.

### 3.1 Google AdMob (advertising)

The Android app integrates **Google Mobile Ads (AdMob)**.

**When ads may appear**

- **Interstitial ad:** After you finish a quiz and leave the results screen (only if you have **not** unlocked ad-free).  
- **Rewarded ad (unlock):** In Settings, you can watch rewarded ads to progress toward **ad-free** (alternative to buying ad-free).  
- **Rewarded ad (optional support):** If you are already ad-free, you may **voluntarily** watch an extra rewarded ad in Settings to advance **Support Squad** ranks. This is optional and only affects in-app gamification.

**What AdMob may process (examples)**

- Device and app identifiers (including the **Android Advertising ID** where permitted)  
- IP address, ad interaction, and technical diagnostics  
- Data used for ad delivery, measurement, and fraud prevention  

The app declares the `com.google.android.gms.permission.AD_ID` permission so advertising identifiers can be used where allowed by Android and your settings.

**Your choices**

- Unlock **ad-free** (purchase or rewarded ads) to stop **interstitial** ads and rewarded ads used **only** for unlocking.  
- **Support** rewarded ads remain **optional** after ad-free.  
- On Android: **Settings → Google → Ads** (or your device manufacturer’s privacy settings) to limit ad personalization.  
- Read Google’s privacy and ad information: [Google Privacy Policy](https://policies.google.com/privacy), [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites), [AdMob & Ads](https://support.google.com/admob/answer/6128543).

The app does **not** currently integrate a separate Google User Messaging Platform (UMP) consent form in code; where required by law, the AdMob SDK or Android may still present privacy or consent flows.

### 3.2 In-app purchases (Google Play)

You can buy a **non-consumable “ad-free”** product or **restore** a previous purchase through **Google Play**.

- Payment and purchase history are handled by **Google**, not by us directly.  
- We only receive what Google Play provides to the app (e.g. that a purchase succeeded) to unlock ad-free on your device.  
- See [Google Play’s privacy information](https://policies.google.com/privacy) and your [Google Account](https://myaccount.google.com/) for payment and purchase data.

### 3.3 Google Play Store

Downloading, updating, or reviewing the app through Google Play involves Google’s own data practices, as described in Google’s policies.

### 3.4 Flutter framework

The app is built with [Flutter](https://flutter.dev). Standard tooling may collect diagnostics during **development**; production Android builds on Google Play do not send your personal data to us through Flutter by default.

---

## 4. Internet and offline use

- **Offline:** Insignia content (images, rank data, quiz logic) is bundled in the app and works without internet for learning and quizzing.  
- **Online required for:** Loading and showing **AdMob** ads, completing **Google Play** purchases, and **restore purchases** in Settings.  
- The app does **not** upload your language or Support Squad counts to the developer.

---

## 5. Android app permissions

| Permission / declaration | Why |
|--------------------------|-----|
| **Internet** | Load ads; communicate with Google Play for purchases. |
| **AD_ID** (`com.google.android.gms.permission.AD_ID`) | Used by Google Play services / AdMob for the advertising identifier where applicable. |

We do **not** request access to your camera, microphone, contacts, or precise location for core app features.

---

## 6. Children’s privacy

Insignia is educational and does not require registration. Because the app can show **personalized or non-personalized ads** through AdMob (depending on configuration and region), parents and guardians should supervise use by children and use Android ad and privacy controls. We do not knowingly collect personal information from children on our own servers.

---

## 7. Data retention

| Data | Retention |
|------|-----------|
| Local preferences & ad-free / Support Squad counters | Until you change them, clear app data, or uninstall |
| AdMob / Google Play data | Per Google’s retention policies |
| Purchases | In your Google Play account history; **Restore purchases** in Settings re-applies ad-free on a new install |

---

## 8. Your rights and choices

Depending on where you live (e.g. **GDPR**, **UK GDPR**, **CCPA/CPRA**), you may have rights to access, delete, or object to certain processing.

- **Data we only store on your device:** Delete via uninstall or **Settings → Apps → Insignia → Storage → Clear data**.  
- **AdMob / Google:** Use [Google’s privacy tools](https://myaccount.google.com/data-and-privacy) and Android ad settings.  
- **Purchases:** Manage in [Google Play](https://play.google.com/store/account) or your Google Account; use **Restore purchases** in the app for ad-free.  
- **Questions:** Contact us (see below). We will respond within a reasonable time.

We do **not** sell your personal information. Google may process data for **ads** and **payments** as described above.

---

## 9. International transfers

AdMob and Google Play may process data in countries outside your own. Google provides its own safeguards and terms for such processing.

---

## 10. Security

Local data uses Android’s standard app sandbox. Keep your device and Google Play account secure for purchases.

---

## 11. Changes to this policy

We may update this Privacy Policy when the Android app changes (e.g. new ad types or features). The **“Last updated”** date at the top will change. Continued use after an update means you accept the revised policy where permitted by law. Material changes may also be noted in Google Play release notes.

---

## 12. Contact

Questions about this Privacy Policy or Insignia’s data practices:

- **Email:** [app.insignia@proton.me](mailto:app.insignia@proton.me)  
- **Google Play:** You can also send feedback via the store listing or your Play account support options.

---

## 13. Legal references (transparency)

This Android app is designed to minimize data collection by the developer. Third-party processing for **advertising** (AdMob) and **in-app purchases** (Google Play) is disclosed above so you can make informed choices. The Google Play listing and in-app experience should be read together with this document.

**Insignia (Android)** — educational content about military insignia; optional ads and ad-free purchase via Google Play; optional **Support Squad** gamification after ad-free.
