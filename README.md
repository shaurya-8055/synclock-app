# SynClock

**Smart reminder & team productivity app for Android.**
Offline-first reminders, natural-language scheduling, exact alarms and shared team reminders.

### [⬇ Download the latest APK](https://github.com/shaurya-8055/synclock-app/releases/latest/download/SynClock.apk) · [See the screenshots](https://shaurya-8055.github.io/synclock/)

That download link always serves the newest build, so it never goes stale.

---

## What it does

- **Offline-first.** Reminders create, edit and fire with no connection, then reconcile against Firestore when one returns.
- **Natural language scheduling.** "Remind me to call mom every Sunday evening" becomes a real recurring schedule, powered by Gemini through the app's own backend. Voice input and text-to-speech included.
- **Alarms that actually fire.** AlarmManager handles exact on-device timing and survives Doze and reboots; FCM delivers updates from teammates.
- **Shared reminders.** Team reminders with role-based access.
- **Backup and export.** Your reminders are yours.

## Stack

Flutter · Dart · Riverpod · Firebase (Auth, Firestore, Messaging) · AlarmManager · Gemini
NestJS on AWS Lambda (41 endpoints) · RevenueCat

## Installing

1. Download the APK from the link above.
2. Android will warn you about installing outside the Play Store — allow your browser or file manager to install unknown apps.
3. Open the file and install.

Requires Android 8.0 or newer.

## Source

The application source is private. This repository exists to distribute builds and screenshots.
Questions about the implementation are welcome — [open an issue](https://github.com/shaurya-8055/synclock-app/issues) or reach me at the links below.

---

Built by [Shaurya Shakya](https://shaurya-8055.github.io/) · [GitHub](https://github.com/shaurya-8055) · [LinkedIn](https://www.linkedin.com/in/shaurya-shakya8055)
