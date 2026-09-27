# Privacy Policy for City Chime

**Last Updated:** September 27, 2026

## Introduction

City Chime ("we," "us," or "our") is an alarm clock and bedside clock app for iOS and Android. This policy explains what information the app collects, why, who helps us process it, how long it is kept, and the choices you have.

**In short:** City Chime has no accounts and never asks for your name, email, or phone number. It does not show ads, does not use an advertising ID, does not track you across other apps, and never sells your data.

## Information We Collect

### Approximate location (optional)

- **What:** Your approximate (not precise) location, only if you allow location access.
- **Why:** To give you local weather and pick local and national news for your spoken wake-up briefing.
- **How it is used:**
  - Your phone turns the location into a city and country using its built-in geocoding service (Apple on iOS, Google on Android).
  - When a briefing is prepared, the approximate coordinates, and the city and country if available, are sent to our server. The server uses the coordinates to get the forecast from Open-Meteo, and the city and country to find relevant news.
  - Your exact coordinates are not stored on our server.
  - Your **country code** is stored with a random install ID so national news can be prepared before your alarm (see "Alarm schedule" below).
  - The spoken weather clip is cached under a rounded area of roughly 10 km (a city area), so nearby users can share it. This cache is not linked to you.
- **Your choice:** You can deny or turn off location access at any time in your device settings. The app keeps working. The briefing simply leaves out local weather and news.

### Alarm schedule (for briefing preparation)

- **What:** For alarms with the wake-up briefing turned on, the alarm's date and time (and whether you use a 12- or 24-hour clock), together with a random ID created when the app is installed.
- **Why:** So our server can prepare your briefing before your alarm rings.
- **Kept for:** Up to 14 days after your last update, then deleted automatically.
- Your alarms themselves (their labels, sounds, and settings) stay on your device.

### Purchases (optional tips)

- City Chime is free. You can choose to leave an optional tip.
- Payment is handled entirely by Apple (App Store) or Google (Google Play). **We never see your card or bank details.**
- RevenueCat, our purchase-management provider, records which tip was bought, when, and the store receipt, linked to an anonymous app user ID. This lets us confirm the purchase and handle refunds.

### Usage analytics

- **Service:** Firebase Analytics (Google).
- **What:** Anonymous events about how the app is used, for example tour steps viewed, whether a permission was allowed, that an alarm was created (and its hour), whether a briefing played, and whether the support sheet was opened or a tip was bought.
- **Why:** To understand which features work and improve the app.
- No names, alarm labels, song titles, or precise location are included.

### Crash reports and diagnostics

- **Service:** Firebase Crashlytics (Google).
- **What:** Crash logs and error reports, device model, operating system version, and app version.
- **Why:** To find and fix bugs.

### Device and app identifiers

- A Firebase installation ID, a push-notification token, RevenueCat's anonymous app user ID, and the random install ID described above.
- **Why:** To deliver notifications, keep purchases and reports tied to the same install, and prepare briefings.
- City Chime does **not** use the advertising ID.

### Music library (Apple Music, iOS)

If you choose a song or playlist from your music library as an alarm sound, the app accesses it only on your device. Your music library is not sent to us.

## How the Wake-Up Briefing Is Made

The spoken briefing is written and voiced on our server by AI services:

- **Anthropic** helps write the briefing text.
- **ElevenLabs** turns the text into speech.

They receive the weather and news text for your briefing, which may include your city name. They do not receive your identifiers, and they only process it for us.

News headlines are fetched by our server from public sources (for example BBC, The Verge, and Hacker News). For local news, your city and region are sent to **ScrapeCreators**, a search provider, to find local headlines. No other information about you is sent.

## Service Providers

We use these providers to run the app. They process data only on our behalf:

| Provider | Purpose | Privacy policy |
|---|---|---|
| Google Firebase / Google Cloud | Our server, analytics, crash reports, notifications, app integrity | https://firebase.google.com/support/privacy |
| Open-Meteo | Weather forecasts | https://open-meteo.com/en/terms#privacy |
| RevenueCat | Tip purchase management | https://www.revenuecat.com/privacy |
| Apple / Google | App Store and Google Play payments; on-device geocoding | https://www.apple.com/legal/privacy/ · https://policies.google.com/privacy |
| Anthropic | Writing the briefing text | https://www.anthropic.com/legal/privacy |
| ElevenLabs | Briefing voice | https://elevenlabs.io/privacy-policy |
| ScrapeCreators | Local news search | https://scrapecreators.com/privacy |

We do **not** sell your data or share it with advertisers or data brokers.

## Data We Do NOT Collect

- Your name, email address, phone number, or postal address
- Precise (GPS-level) location
- Advertising ID or cross-app tracking data
- Contacts, photos, messages, or files
- Health or fitness data
- Your alarm labels or the contents of your music library

## How Long We Keep Data

- **Alarm schedule and country code:** up to 14 days after your last update.
- **Cached weather clips:** about 25 hours, and not linked to you.
- **Analytics and crash reports:** according to Firebase's retention settings.
- **Purchase records:** as long as needed to confirm purchases, handle refunds, and meet legal and tax obligations.
- Data stored on your device is deleted when you uninstall the app.

## Security

All data sent by the app is encrypted in transit (HTTPS). The app blocks unencrypted connections in its release builds.

## Your Rights and Choices

- Turn location access or notifications off at any time in your device settings.
- Uninstall the app to delete everything stored on your device.
- Ask us to access or delete your data (see below).

## Delete Your Data

Email **rushuicode@gmail.com** with the subject **"Delete my data"**. Because City Chime has no accounts, please include the date you installed the app, and a tip receipt if you have one, so we can find your records. We will delete your analytics, crash, and briefing records, and your purchase records where the law allows, within 30 days, and confirm by email.

## Children

City Chime is not directed to children under 13, and we do not knowingly collect information from children.

## Contact Us

For privacy questions, contact: **rushuicode@gmail.com**

## Changes to This Policy

We may update this policy from time to time. The "Last Updated" date at the top shows when it last changed.
