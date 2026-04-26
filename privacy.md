# Privacy Policy

**Effective date:** April 26, 2026
**Last updated:** April 26, 2026

This Privacy Policy describes how Helm ("we", "us", "our", or "the App"), operated by Devalchemist Labs ("Devalchemist Labs"), collects, uses, and shares information when you use the Helm mobile application ("the Service").

By using Helm, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information We Collect

### 1.1 Information you provide directly

- **Account information.** When you sign in with Google, we receive your email address, display name, and Google account user ID (UID). We do not receive your Google password.
- **Audio recordings.** Helm records meeting audio that you initiate. Recording is always user-initiated — Helm does not record without an explicit start command.
- **Transcripts and summaries.** Audio you record is transcribed, and transcripts are summarized using AI. The resulting text is stored in your account.
- **Meeting metadata.** Titles, project assignments, timestamps, and notes you create within the App.
- **Feedback and correspondence.** When you contact us at feedback@helm.app or other support addresses.

### 1.2 Information collected automatically

- **Device information.** Operating system version, device model, app version, and crash reports for diagnostic purposes.
- **Usage analytics.** Aggregate, non-identifying events such as feature usage frequency and session duration. We use Firebase Analytics for this purpose.
- **Crash reports.** Stack traces and device state at the time of a crash, collected via Firebase Crashlytics.

### 1.3 Information we do NOT collect

- We do not collect biometric data. Biometric authentication (fingerprint/face) happens entirely on your device — we never receive or store biometric templates.
- We do not access your contacts, calendar, photos, or files outside of audio you record within the App.
- We do not collect location data.
- We do not use advertising identifiers (AAID/IDFA) and do not serve ads.

---

## 2. How We Use Your Information

We use the information we collect to:

- Provide, maintain, and improve the Service (recording, transcription, summarization, storage)
- Authenticate your identity and secure your account
- Sync your data across your devices
- Send you transactional communications (e.g., security alerts, account changes)
- Diagnose and fix crashes, bugs, and performance issues
- Comply with legal obligations

We do **not** sell your personal information to third parties.
We do **not** train AI models on your audio, transcripts, or summaries.
We do **not** share your meeting content with anyone outside the third-party processors listed below.

---

## 3. Third-Party Services

Helm relies on the following third-party services to deliver core functionality. By using Helm you consent to your information being processed by these services. Each operates under its own privacy policy.

| Service | Provider | Purpose | Data shared |
|---|---|---|---|
| **Firebase Authentication** | Google | Account sign-in | Email, Google UID |
| **Cloud Firestore** | Google | Storing meeting metadata, transcripts, summaries | Account UID, meeting data |
| **Firebase Cloud Storage** | Google | Storing audio recording files | Account UID, audio files (encrypted in transit and at rest) |
| **Firebase Crashlytics** | Google | Crash diagnostics | Device info, stack traces (no audio or transcripts) |
| **Firebase Analytics** | Google | Aggregate usage metrics | Anonymized event data |
| **Deepgram Nova-3** | Deepgram, Inc. | Real-time audio transcription | Audio segments during transcription only — Deepgram does not retain audio per their data processing addendum |
| **Anthropic Claude** | Anthropic, PBC | AI-generated summaries and coaching prompts | Transcript text — Anthropic does not train models on API inputs per their commercial terms |
| **RevenueCat** | RevenueCat, Inc. | In-app purchase management (if you upgrade to a paid tier) | Account UID, purchase metadata |
| **Google Identity Services** | Google | Google Sign-In | Authentication tokens |

**Sub-processor links:**
- Firebase / Google: https://firebase.google.com/support/privacy
- Deepgram: https://deepgram.com/privacy
- Anthropic: https://www.anthropic.com/legal/privacy
- RevenueCat: https://www.revenuecat.com/privacy

---

## 4. Data Retention

- **Audio recordings:** retained until you delete them. You can delete recordings individually from within the App at any time. When you delete a recording, the file is removed from Cloud Storage within 24 hours.
- **Transcripts and summaries:** retained until you delete the parent meeting.
- **Account data:** retained while your account is active. If you delete your account, all associated data is deleted within 30 days.
- **Crash and analytics data:** retained for up to 90 days, then aggregated or deleted.
- **Backups:** deleted backups may persist in encrypted backup systems for up to 35 days before permanent deletion.

---

## 5. Data Security

We take the following measures to protect your information:

- **Local encryption.** All data stored on your device is encrypted using SQLCipher (database) and Android Keystore (encryption keys).
- **Biometric lock.** Optional biometric authentication prevents unauthorized access to the App on your device.
- **Encrypted transport.** All network traffic uses TLS 1.2 or higher.
- **Encrypted cloud storage.** Audio files in Cloud Storage are encrypted at rest and in transit. Firestore data is encrypted at rest.
- **Account isolation.** Cloud data is scoped to your authenticated account UID — other users cannot access your meetings.
- **Limited access.** No Devalchemist Labs employee accesses your meeting content except as required to investigate a specific support request you have raised, and only with your consent.

No method of transmission or storage is 100% secure. While we strive to protect your information, we cannot guarantee absolute security.

---

## 6. Your Rights

Depending on your jurisdiction, you may have the following rights:

- **Access.** Request a copy of the personal information we hold about you.
- **Correction.** Request correction of inaccurate or incomplete information.
- **Deletion.** Request that we delete your personal information.
- **Portability.** Request your data in a portable, machine-readable format.
- **Withdrawal of consent.** Withdraw consent at any time by deleting your account.
- **Objection.** Object to our processing of your information.

To exercise any of these rights, email **privacy@helm.app**. We will respond within 30 days.

### EU/EEA users (GDPR)

Our legal basis for processing:
- **Contract performance** — to deliver the Service you requested
- **Consent** — for optional analytics
- **Legitimate interest** — for crash diagnostics and Service improvement

You have the right to lodge a complaint with your local data protection authority.

### California users (CCPA/CPRA)

We do not sell or share personal information for cross-context behavioral advertising. You may request access, deletion, or correction of your data using the contact above.

---

## 7. Children's Privacy

Helm is not directed at children under 13 (or 16 in the EU/EEA). We do not knowingly collect information from children. If you believe a child has provided us with personal information, please contact us at privacy@helm.app and we will promptly delete it.

---

## 8. International Data Transfers

Your information may be transferred to and processed in countries other than your own, including the United States, where our service providers are located. We rely on appropriate safeguards (e.g., Standard Contractual Clauses) where required.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of material changes by posting the updated policy in-app and updating the "Last updated" date above. Continued use of Helm after changes constitutes acceptance.

---

## 10. Contact

For privacy questions, data requests, or concerns:

**Email:** privacy@helm.app
**Support:** feedback@helm.app
**Operator:** Devalchemist Labs
**Address:** Available on request — email privacy@helm.app

---

*This document is provided as a starting point. Before publishing, have it reviewed by counsel licensed in your jurisdiction(s) of operation. Specific obligations vary by country, region, and the categories of users you serve.*
