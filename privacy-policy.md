# Privacy Policy

**Gym App**
*Last updated: 4 April 2026*

## Overview

Gym App is a workout planner and interval timer. Your workout data belongs to you — the app is designed to keep it on your device. This policy explains what data leaves your device, when, and why.

---

## Data Stored On-Device

All workout data you create — exercise library, workout sessions, interval configurations, cardio machines, scheduled workouts, completed workout logs, and preferences — is stored locally on your device. This data does not leave your device unless you enable one of the optional features described below.

---

## Optional Features That Send Data Externally

### Cloud Sync

**iOS — iCloud Sync:** Your workout data is synchronised across your Apple devices using Apple's iCloud Key-Value Store. This data is transmitted to and stored on Apple's servers under your Apple ID. We do not have access to this data. iCloud sync uses a small amount of your iCloud storage (typically under 1 MB). See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) for details.

**Android — Google Drive Sync:** If you sign in with your Google account, your workout data is backed up to your personal Google Drive. This data is transmitted to and stored on Google's servers under your Google account. We do not have access to this data. See [Google's Privacy Policy](https://policies.google.com/privacy) for details. Sign-in is optional — you can use the app without it.

### Strava Integration

If you choose to connect your Strava account, completed workouts are uploaded to Strava as activity summaries. The data sent includes your workout name, duration, exercises performed, and sets/reps/weights, formatted as a text description. When you first connect, you may be prompted to upload existing completed workouts. This data is transmitted to Strava's servers and is governed by [Strava's Privacy Policy](https://www.strava.com/legal/privacy). Connecting Strava is entirely optional. You can disconnect at any time in Settings → Connected Accounts. Strava OAuth tokens are stored securely on your device using the iOS Keychain.

### Calendar Sync

If you enable Calendar Sync, scheduled workout names and dates are written to a calendar on your device named "Gym App Workouts." This is an on-device operation. If your device syncs its calendar to iCloud or Google Calendar, those providers' privacy policies apply.

### Feedback Submissions

If you submit feedback via Settings → Feedback, the following information is sent to our feedback portal:

- Your message (free text you provide)
- Category (Bug Report, Feature Request, or General)
- Platform (iOS or Android)
- App version (e.g. 1.0.0)
- Operating system version (e.g. iOS 18.3)

No name, email address, or account information is collected. Submissions are anonymous. This data is stored on Microsoft Azure (Table Storage) and processed using Azure Functions. It is used only to improve the app. We do not sell or share this data with third parties beyond the infrastructure providers listed below.

### Exercise Demos

Exercise demo animations are fetched on-demand from ExerciseDB (exercisedb.dev), a public exercise database. When you download a demo, a request is made to their CDN containing only the exercise identifier. No personal data is sent. Downloaded demos are cached locally on your device.

---

## Third-Party Service Providers

The following third-party services process data on our behalf:

| Service | Purpose | Data Processed |
|---------|---------|----------------|
| Apple (iCloud) | Cloud sync | Workout data (encrypted by Apple) |
| Google (Drive) | Cloud sync (Android) | Workout data (encrypted by Google) |
| Strava | Activity upload | Workout summaries (user-initiated) |
| Microsoft Azure | Feedback portal | Anonymous feedback submissions |
| ExerciseDB | Exercise demos | Exercise identifier only |

We do not use any analytics, advertising, or tracking services.

---

## Subscriptions & In-App Purchases

The app offers optional subscriptions billed through the Apple App Store. All purchase and payment processing is handled entirely by Apple using StoreKit. We do not receive, store, or transmit your payment information. No third-party purchase SDKs are used. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) for details.

---

## Speech & Audio

The app uses your device's built-in text-to-speech engine for voice countdown cues. Speech synthesis is performed entirely on-device — no audio data is sent to external services.

---

## Children's Privacy

The app does not knowingly collect personal data from children under 13. Feedback submissions are anonymous. Cloud sync features rely on the device owner's Apple or Google account.

---

## Changes to This Policy

If this policy changes materially, the updated version will be posted here with a new "Last updated" date.

---

## Contact

For questions about this policy, please visit [github.com/The-Magic-Apps/Gym](https://github.com/The-Magic-Apps/Gym).
