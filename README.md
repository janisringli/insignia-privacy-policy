# Privacy Policy for Insignia App

**Last Updated:** December 2, 2025

## Introduction

This Privacy Policy describes how the Insignia mobile application ("we," "our," or "the app") collects, uses, and protects your information when you use our service. Insignia is designed to help users learn about military ranks, branches, functions, and special insignia.

## Information We Collect

### Information We Do NOT Collect

Insignia is designed with privacy in mind. **We do NOT collect, store, or transmit any personal information to external servers.** This includes:

- Personal identification information (name, email, phone number)
- Device identifiers or advertising IDs
- Location data
- Usage analytics
- Crash reports sent to external services
- Any form of user-generated content

### Information Stored Locally

The app stores the following information locally on your device only:

- **Language Preference**: Your selected language setting (German, French, Italian, or English) is stored using SharedPreferences to maintain your preferred language across app sessions
- **Quiz Progress**: Temporary quiz scores and progress are stored in device memory during active quiz sessions but are not persisted between app restarts

## How We Use Information

The locally stored information is used solely to:

- Remember your preferred language setting when you restart the app
- Provide a consistent user experience in your chosen language
- Display quiz results during active quiz sessions

## Data Security

Since all data remains on your device:

- No data transmission occurs between your device and external servers
- Your language preference is stored using Android/iOS standard secure storage mechanisms
- No encryption keys or passwords are required as no sensitive data is processed

## Third-Party Services

### Flutter Framework

The app is built using Google's Flutter framework, which may collect standard diagnostic information for debugging purposes during development. This does not affect the production version of the app.

### App Stores

When you download the app from Google Play Store or Apple App Store, those platforms may collect information according to their own privacy policies. We have no control over this data collection.

## Children's Privacy

Insignia is suitable for all ages and does not collect any personal information from users of any age. The app is educational in nature and focuses solely on displaying military insignia information.

## Data Retention

- **Language Preference**: Stored until you manually change it or uninstall the app
- **Quiz Data**: Cleared when you exit the quiz or restart the app
- **App Data**: All locally stored data is automatically deleted when you uninstall the app

## Your Rights and Choices

You have complete control over your data:

- **Language Settings**: Change or reset your language preference at any time through the app's settings menu
- **Data Deletion**: Uninstall the app to completely remove all stored data
- **No Account Required**: The app functions without any user registration or account creation

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the "Last Updated" date at the top of this policy. Continued use of the app after any changes constitutes acceptance of the updated policy.

## App Permissions

The Insignia app requests minimal permissions:

### Android Permissions

- **Internet**: Required only for initial app installation and updates (no data is transmitted during normal app usage)
- **Storage**: Used only for local data storage of language preferences

### iOS Permissions

- **Local Storage**: Used only for storing language preferences locally on your device

## Offline Functionality

Insignia is designed to work completely offline after installation:

- All insignia images and data are bundled with the app
- No internet connection is required for normal operation
- Quiz functionality works entirely offline
- Language switching works without network access

## Contact Information

If you have any questions about this Privacy Policy or the app's data practices, you can contact us through:

- **App Store Reviews**: Leave feedback through google Playstore

## Compliance

This app complies with:

- **GDPR** (General Data Protection Regulation) - No personal data is collected or processed
- **CCPA** (California Consumer Privacy Act) - No personal information is sold or shared
- **COPPA** (Children's Online Privacy Protection Act) - No data collection from children or any users

## Technical Details

### Data Storage Implementation

- Language preferences are stored using Flutter's `shared_preferences` package
- Data is stored in platform-specific secure storage (Android SharedPreferences / iOS UserDefaults)
- No databases or external storage services are used

### Data Flow

1. User selects language → Stored locally on device
2. User takes quiz → Temporary data in device memory
3. User exits quiz → Temporary data is cleared
4. User uninstalls app → All data is permanently deleted

---

**Summary:** Insignia is a privacy-focused educational app that stores only your language preference locally on your device. No personal information is collected, transmitted, or shared with any third parties.
