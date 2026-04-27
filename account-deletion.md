---
title: Account & Data Deletion — Helm
---

# Account and Data Deletion — Helm

**App:** Helm: Meeting Intelligence
**Developer:** Devalchemist Labs
**Package:** `com.devalchemistlabs.helm`

This page explains how to request deletion of your Helm account and all associated data.

---

## How to request account deletion

To delete your Helm account and all associated data, send an email to:

# **privacy@helm.app**

Please include the following so we can verify your identity and locate your data:

- Your full name
- The email address associated with your Helm account
- The subject line: **"Account deletion request"**

We will:

1. Confirm receipt within **3 business days**
2. Verify the request is from the account owner (we will email you a verification code at the registered address)
3. Delete your account and all associated data within **30 days** of verification
4. Email you a confirmation when deletion is complete

There is no charge for account deletion.

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
| Crash reports linked to your user ID | Firebase Crashlytics | Within 90 days (per Crashlytics retention policy) |
| In-app purchase records | RevenueCat | Within 30 days (purchase history may be retained for tax / accounting compliance) |

### Backups

Backups of our systems may retain a copy of your data for up to **35 days** after deletion before permanent removal. After this period, no copy of your data remains on our servers.

### Data we may retain

We may retain limited information where required by law or for legitimate business purposes:

- Aggregate, anonymized analytics that cannot be used to identify you
- Records required for tax, accounting, or legal compliance (typically 7 years for financial records)
- Information required to defend against pending legal claims

---

## Delete some data without deleting your account

You can delete individual items from inside the app at any time:

- **Single meeting** — open the meeting → tap the menu (⋮) → **Delete**
- **All recordings in a project** — open the project → **Delete project**

For bulk deletion requests that go beyond what the app supports, email **privacy@helm.app** with the subject **"Data deletion request"** and describe what you'd like removed. The same 30-day timeline applies.

---

## Questions or concerns?

- **Privacy:** privacy@helm.app
- **General support:** feedback@helm.app
- **Legal:** legal@helm.app

This deletion process is part of our broader commitments described in our [Privacy Policy](privacy.html).
