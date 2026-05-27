# Privacy Policy for Sudoku ZenX

**Developer:** GameSTEMx
**Last updated:** May 27, 2026

This Privacy Policy describes how **Sudoku ZenX** ("the app", "we", "us") collects, uses, and shares information when you use our mobile application.

## 1. Information We Collect

### 1.1 Information you provide
We do not require you to create an account to play Sudoku ZenX. The app may collect information when you choose to:

- **Sign in with Google Play Games Services** — your Google Play Games player ID, display name, and avatar, used to sync your game progress and (after you choose a nickname) display you on the public leaderboard.
- **Choose a leaderboard nickname** — an optional public display name (letters, digits, underscore; 3–20 chars) that other players can see next to your score on the in-app leaderboard. You can change it once every 60 days.
- **Make an in-app purchase** — purchase processing is handled entirely by Google Play Billing. We do not receive or store your payment information.

### 1.2 Information collected automatically

- **Game progress data** — puzzle states, statistics, settings, and achievements, stored locally on your device and optionally synced via Google Play Games Saved Games and Google Firebase Firestore when you are signed in (see section 3).
- **Advertising identifiers** — Google AdMob, our advertising partner, collects your device's advertising ID and limited usage data to serve ads. See section 3.
- **Analytics events** — Google Firebase Analytics records basic gameplay events (e.g. game started, game completed, screen views) and the standard device/app metadata Firebase attaches to those events. We use this only to understand aggregate usage and improve the app.
- **Crash and diagnostic data** — Google Play services may collect basic crash logs to help us improve the app. We do not associate this with your identity.

We do not collect: your name, email, phone number, location, photos, contacts, or any other personal information beyond what is described above.

## 2. How We Use Information

We use the information collected to:

- Save and sync your game progress across your devices
- Show in-app advertisements through Google AdMob
- Process in-app purchases through Google Play Billing
- Diagnose crashes and improve app stability
- Comply with legal obligations

## 3. Third-Party Services

Sudoku ZenX uses the following third-party services. Each has its own privacy policy:

| Service | Purpose | Privacy Policy |
|---------|---------|---------------|
| **Google Play Services** | Core platform integration | https://policies.google.com/privacy |
| **Google Play Games Services** | Sign-in, cloud save, achievements | https://policies.google.com/privacy |
| **Google Firebase Authentication** | Linking your Play Games identity to our cloud database | https://firebase.google.com/support/privacy |
| **Google Firebase Firestore** | Cloud-side game progress, leaderboard, and nickname registry | https://firebase.google.com/support/privacy |
| **Google Firebase Analytics** | Aggregate usage analytics | https://firebase.google.com/support/privacy |
| **Google AdMob** | In-app advertising | https://policies.google.com/technologies/ads |
| **Google Play Billing** | In-app purchases | https://policies.google.com/privacy |

When you are signed in, the app writes the following to Firestore under a document keyed by your anonymized Firebase user ID: your game progress, your chosen nickname, your total points, and the timestamp of your last nickname change. Your nickname and points are also published to a public leaderboard document so other players can see them. **No real name, email, phone number, or device location is sent to Firestore.**

AdMob may collect your advertising ID and use it to deliver personalized ads. You can reset your advertising ID or opt out of personalized ads at any time through your device settings (**Settings → Google → Ads**).

## 4. Data Storage and Retention

- **Local data:** game progress and settings are stored on your device and can be deleted by uninstalling the app or clearing app data.
- **Play Games cloud saves:** stored in your Google account. You can delete these at any time via the Google Play Games app.
- **Firestore cloud data:** your game progress, nickname, points, and leaderboard entry are retained while your account is active. You can erase them in-app via **Menu → Settings → Reset all progress**, or by emailing us a deletion request at the address in section 9. On request we delete your `users/{uid}`, `leaderboard/{uid}`, and reserved nickname records.
- **Analytics data:** retention is governed by Google Firebase Analytics' default policy (typically 14 months for event-level data).
- **Advertising data:** retention is governed by Google AdMob's policy.

## 5. Children's Privacy

Sudoku ZenX is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe we have inadvertently collected such information, please contact us and we will delete it.

## 6. Your Rights

Depending on your jurisdiction, you may have rights to:

- Access the information we hold about you
- Request deletion of your data
- Opt out of personalized advertising
- Withdraw consent for data processing

To exercise these rights, contact us at the email below — we can delete your Firestore data (game progress, nickname, leaderboard entry) on request. To delete Google-managed data (Play Games saves, advertising ID), use the Google account controls at https://myaccount.google.com.

## 7. Security

We rely on Google's infrastructure (Google Play, Google Play Games, Google Firebase, Google AdMob, Google Play Billing) for data storage and transmission. Firestore data is transmitted over TLS and stored in Google's Iowa (us-central1) region. While we take reasonable steps to protect your information, no method of transmission over the Internet is 100% secure.

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be communicated through an update to the app or a notice on this page. The "Last updated" date at the top reflects the most recent revision.

## 9. Contact Us

If you have questions or concerns about this Privacy Policy or your data, contact us at:

**Email:** ganesh.istemx@gmail.com
**App package:** com.zenx.sudoku
