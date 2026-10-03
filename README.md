# Privacy Policy for Insignia (Android)

**Last updated:** October 3, 2026  
**App version:** 2.0.0 (see the [Google Play](https://play.google.com) listing for the build you installed)

**Platform:** Insignia is distributed **only on Android** via Google Play. This policy applies to the Android app.

## Introduction

Insignia (“the app”) is an educational app about Swiss military ranks, branches, functions, and insignia, with a guide for your military service (abbreviations, career paths, rights and duties, pay calculator, radio alphabet, packing list, and a countdown for basic training). This Privacy Policy explains **what data the app handles**, **what stays on your device**, and **which third parties may process data** when you use features such as advertising or in-app purchases on Android.

**Developer / data controller:** Janis Ringli (individual developer of Insignia).  
We do **not** operate our own user accounts, login servers, or analytics backend for this app.

## Summary (plain language)

| Topic | What happens |
|--------|----------------|
| **Our own servers** | We do **not** collect or store your personal data on servers we run. |
| **On your device** | Language, quiz settings, ad-free status, ad progress, optional “Support Squad” progress, your RS countdown, and your packing list are saved **locally** on your phone or tablet (see below). |
| **Notifications** | Optional. If you allow them, the RS countdown schedules reminders **locally** on your device; no push server is involved. |
| **Advertising** | **Google AdMob** may show ads and process data (e.g. Android Advertising ID) under [Google’s policies](https://policies.google.com/privacy). For the quiz ad, AdMob may also let **Meta Audience Network** bid to show an ad (see 3.2). |
| **Privacy settings** | Where required (EEA, UK, Switzerland), you can change your ad consent at any time in **Settings → Privacy settings**. |
| **Purchases** | **Google Play** processes payments and related data when you buy or restore “ad-free.” |
| **Offline use** | Browsing insignia, quizzes, and the guide work **offline**; **ads and Play Store purchases need an internet connection**. |

---

## 1. Data we store on your device (not sent to us)

The app uses Android **SharedPreferences** (via Flutter’s `shared_preferences` package). This information is stored **only on your device** and is **not transmitted to the developer’s servers**:

| Stored item | Purpose |
|-------------|---------|
| **Selected language** | Remember German, French, Italian, or English. |
| **Quiz difficulty** | Remember your quiz mode preference (e.g. free text). |
| **Quiz category** | Remember the quiz category you last picked (e.g. ranks, branches). |
| **Ad-free unlocked** | Remember whether you unlocked ad-free (purchase or rewarded ads). |
| **Rewarded ad progress** | Count how many rewarded ads you watched toward unlocking ad-free (default target: 12). |
| **Optional support ad count** | Count voluntary “support” rewarded ads after you are ad-free (used only for **Support Squad** rank display—gamification, not a real military status). |
| **“Don’t show again” for ad-free prompt** | Remember if you dismissed the post-quiz suggestion to go ad-free in Settings. |
| **RS countdown** (optional) | Only if you start the countdown: the start date of your basic training (RS), its length, and whether you serve as a Durchdiener; also the official start date of an RS you declined or hid. Used only to show the countdown and to schedule its reminders. |
| **Packing list** | Which items of the RS packing list you ticked off. |
| **Home screen widget** (optional) | If you place the RS countdown widget, the countdown settings above and the widget texts are also kept in the widget’s storage on your device, so it can show the days without opening the app. |
| **Notification prompt shown** | Remember that the app already asked once whether you want to allow notifications. |
| **App launch count and review requests** | Count app starts and remember when the app last asked for a Google Play rating (and whether it already asked after your RS), so you are not asked too often. |

**Quiz session data** (current score, questions in progress) lives in app memory during a quiz and is not uploaded by us.

**Pay calculator:** The monthly income you may enter in the Sold & EO calculator is used only for the calculation on screen. It is **not saved** and is gone when you leave the page.

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

- **Interstitial ad:** After you finish a quiz and leave the results screen, or when you leave a quiz after answering at least a third of its questions (at most one per quiz round; only if you have **not** unlocked ad-free).  
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
- **In the app:** Where required by law (EEA, UK, Switzerland), open **Settings → Privacy → Privacy settings** at any time to review or change your consent, including which ad partners may process your data.  
- On Android: **Settings → Google → Ads** (or your device manufacturer’s privacy settings) to limit ad personalization.  
- Read Google’s privacy and ad information: [Google Privacy Policy](https://policies.google.com/privacy), [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites), [AdMob & Ads](https://support.google.com/admob/answer/6128543).

**Consent:** The app uses Google’s **User Messaging Platform (UMP)**. Where required by law (e.g. in the EEA, the UK, and Switzerland), a consent form is shown before ads are requested, and ads are only loaded once Google’s consent check allows it. The Mobile Ads SDK (including the Meta adapter, see 3.2) is only started after this consent check allows ads; starting it does not load an ad. Your choice applies to Google and to every ad partner listed in the form, including Meta.

### 3.2 Meta Audience Network (via AdMob mediation)

For the **interstitial ad after a quiz**, AdMob uses **mediation**: besides Google, **Meta Audience Network** (Meta Platforms Ireland Ltd. / Meta Platforms, Inc.) may bid to show the ad. The rewarded ads in Settings are served by Google only.

- To take part in the auction, the Meta Audience Network SDK included in the app may receive device and app information such as the **Android Advertising ID** (where permitted), IP address, device model, operating system, app version, and ad interaction data (e.g. impressions and clicks), for ad delivery, measurement, and fraud prevention.  
- In the EEA, UK, and Switzerland, Meta only takes part if your consent choice in the privacy form allows it; you can change this in **Settings → Privacy settings**.  
- Meta may cache video ads on your device through a local connection (`127.0.0.1`); this traffic does not leave your device.  
- Meta processes this data under its own policy: [Meta Privacy Policy](https://www.facebook.com/privacy/policy/).

### 3.3 In-app purchases (Google Play)

You can buy a **non-consumable “ad-free”** product or **restore** a previous purchase through **Google Play**.

- Payment and purchase history are handled by **Google**, not by us directly.  
- We only receive what Google Play provides to the app (e.g. that a purchase succeeded) to unlock ad-free on your device.  
- See [Google Play’s privacy information](https://policies.google.com/privacy) and your [Google Account](https://myaccount.google.com/) for payment and purchase data.

### 3.4 Google Play Store

Downloading, updating, or reviewing the app through Google Play involves Google’s own data practices, as described in Google’s policies.

At a few positive moments (for example after a good quiz result or a completed packing list, at most every 14 days, and only for installs from Google Play) the app may ask Google Play to show its **In-App Review** dialog. Google decides whether the dialog appears; your rating and review go directly to Google Play, and the app does not learn whether or how you rated it.

### 3.5 Flutter framework

The app is built with [Flutter](https://flutter.dev). Standard tooling may collect diagnostics during **development**; production Android builds on Google Play do not send your personal data to us through Flutter by default.

---

## 4. Internet and offline use

- **Offline:** Insignia content (images, rank data, quiz logic, guide chapters, calculator) is bundled in the app and works without internet for learning and quizzing.  
- **Online required for:** Loading and showing **AdMob** ads, completing **Google Play** purchases, and **restore purchases** in Settings.  
- The app does **not** upload your language, Support Squad counts, RS countdown, or packing list to the developer.

---

## 5. Android app permissions

| Permission / declaration | Why |
|--------------------------|-----|
| **Internet** | Load ads; communicate with Google Play for purchases. |
| **AD_ID** (`com.google.android.gms.permission.AD_ID`) | Used by Google Play services / AdMob for the advertising identifier where applicable. |
| **Notifications** (`android.permission.POST_NOTIFICATIONS`, Android 13+) | Optional. Asked only when you start the RS countdown, so the app can remind you of dates of your basic training (currently a congratulation at the start of week 12). Notifications are scheduled locally on your device; no push service or server is involved. The dates stay on your device; you can turn notifications off at any time in the Android settings. |

We do **not** request access to your camera, microphone, contacts, or precise location for core app features.

---

## 6. Children’s privacy

Insignia is educational and does not require registration. Because the app can show **personalized or non-personalized ads** through AdMob and Meta Audience Network (depending on configuration and region), parents and guardians should supervise use by children and use Android ad and privacy controls. We do not knowingly collect personal information from children on our own servers.

---

## 7. Data retention

| Data | Retention |
|------|-----------|
| Local preferences, ad-free / Support Squad counters, RS countdown, packing list | Until you change them (e.g. remove the countdown), clear app data, or uninstall |
| Scheduled notifications | Until they are shown, you remove the countdown, or you uninstall |
| AdMob / Google Play data | Per Google’s retention policies |
| Meta Audience Network data | Per Meta’s retention policies |
| Purchases | In your Google Play account history; **Restore purchases** in Settings re-applies ad-free on a new install |

---

## 8. Your rights and choices

Depending on where you live (e.g. **GDPR**, **UK GDPR**, **CCPA/CPRA**), you may have rights to access, delete, or object to certain processing.

- **Data we only store on your device:** Delete via uninstall or **Settings → Apps → Insignia → Storage → Clear data**.  
- **Ad consent:** Change it at any time in **Settings → Privacy settings** (shown where required by law).  
- **AdMob / Google:** Use [Google’s privacy tools](https://myaccount.google.com/data-and-privacy) and Android ad settings.  
- **Meta:** See [Meta’s privacy tools](https://www.facebook.com/privacy/policy/) for data Meta processes as an ad partner.  
- **Purchases:** Manage in [Google Play](https://play.google.com/store/account) or your Google Account; use **Restore purchases** in the app for ad-free.  
- **Questions:** Contact us (see below). We will respond within a reasonable time.

We do **not** sell your personal information. Google may process data for **ads** and **payments**, and Meta for **ads**, as described above.

---

## 9. International transfers

AdMob, Google Play, and Meta Audience Network may process data in countries outside your own (e.g. the United States). Google and Meta provide their own safeguards and terms for such processing.

---

## 10. Security

Local data uses Android’s standard app sandbox. Keep your device and Google Play account secure for purchases.

---

## 11. Changes to this policy

We may update this Privacy Policy when the Android app changes (e.g. new ad types or features). The **“Last updated”** date at the top will change. Continued use after an update means you accept the revised policy where permitted by law. Material changes may also be noted in Google Play release notes.

---

## 12. Contact

Questions about this Privacy Policy or Insignia’s data practices:

- **Email:** [janis.ringli@gmail.com](mailto:janis.ringli@gmail.com)  
- **Google Play:** You can also send feedback via the store listing or your Play account support options.

---

## 13. Legal references (transparency)

This Android app is designed to minimize data collection by the developer. Third-party processing for **advertising** (AdMob, Meta Audience Network via AdMob mediation) and **in-app purchases** (Google Play) is disclosed above so you can make informed choices. The Google Play listing and in-app experience should be read together with this document.

**Insignia (Android)** — educational content about military insignia and a guide for military service; optional ads (Google AdMob, Meta Audience Network via mediation) with in-app privacy settings, and ad-free purchase via Google Play; optional local notifications for the RS countdown; optional **Support Squad** gamification after ad-free.
