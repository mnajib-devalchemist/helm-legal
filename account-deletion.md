---
title: Account & Data Deletion — Helm
---

# Account and Data Deletion — Helm

**App:** Helm: Meeting Intelligence
**Developer:** Devalchemist Labs
**Package:** `com.devalchemistlabs.helm`

This page explains how to request deletion of your Helm account and all associated data.

---

## How to request deletion

### Option 1 (recommended): Delete from inside the app

1. Open the **Helm** app on your device
2. Go to your **Profile** tab
3. Scroll to **Account** → tap **Delete account**
4. Confirm the deletion prompt

Your account and all associated data are removed from our systems within 30 days.

### Option 2: Email request

If you cannot access the app for any reason, you can request deletion by email.

**Send an email to:** privacy@helm.app

Please include the following so we can verify your identity and locate your data:

- Your full name
- The email address associated with your Helm account
- The subject line: **"Account deletion request"**

We will:

1. Confirm receipt within **3 business days**
2. Verify the request is from the account owner (we will email you a verification code at the registered address)
3. Delete your account and all associated data within **30 days** of verification
4. Email you a confirmation when deletion is complete

---

## What gets deleted

When you request account deletion, we permanently delete:

| Data type | Where stored | Deletion timeline |
|---|---|---|
| Account profile (email, user ID, display name) | Firebase Authentication | Within 30 days |
| Meeting metadata (titles, projects, timestamps) | Cloud Firestore | Within 30 days |
| Audio recordings | Firebase Cloud Storage | Within 30 days |
| Transcripts and AI summaries | Cloud Firestore | Within 30 days |
| Project organization data | Cloud Firestore | Within 30 days |
| Crash reports linked to your user ID | Firebase Crashlytics | Within 90 days (Crashlytics retention policy) |
| In-app purchase records | RevenueCat | Within 30 days (purchase history may be retained for tax / accounting compliance) |

### Backups

Backups of our systems may retain a copy of your data for up to **35 days** after deletion before permanent removal. After this period, no copy of your data remains on our servers.

### Data we may retain

We may retain limited information where required by law or for legitimate business purposes:

- Aggregate, anonymized analytics that cannot be used to identify you
- Records required for tax, accounting, or legal compliance (typically 7 years for financial records)
- Information required to defend against pending legal claims

---

## Want to delete some data without deleting your account?

You can delete individual items from inside the app at any time:

- **Single meeting** — open the meeting → tap the menu (⋮) → **Delete**
- **All recordings in a project** — open the project → **Delete project**
- **All cloud-synced data, keep account active** — Profile → **Sign out and clear local data**

For bulk deletion requests beyond what the app supports, email **privacy@helm.app** with the subject **"Data deletion request"** and describe what you'd like removed.

---

## Questions or concerns?

- **Privacy:** privacy@helm.app
- **General support:** feedback@helm.app
- **Legal:** legal@helm.app

This deletion process is part of our broader commitments described in our [Privacy Policy](privacy.html).
