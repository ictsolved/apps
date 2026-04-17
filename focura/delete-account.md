---
layout: page
title: Delete Account & Data — Focura
permalink: /focura/delete-account
app_name: Focura
app_icon: assets/apps/focura/icon.png
screenshot: assets/apps/focura/screenshots/focura-screenshot.jpg
app_url: /focura
include_in_header: false
---

# Delete Account & Data

**App:** Focura – Deep Focus System
**Developer:** ICT Solved!

---

## Delete All Your Data (Without Deleting Your Account)

You can delete all focus session data directly inside the app at any time, without deleting your Google account or contacting us.

**Steps:**

1. Open the **Focura** app
2. Go to **Settings**
3. Scroll to the **Account** section
4. Tap **Reset All Data**
5. Confirm when prompted

**What gets deleted:**
- All XP and level progress
- All streak history
- All completed sessions
- All achievements
- If you are signed in, your cloud-synced data is also deleted from Firebase Firestore

**What is retained:**
- Your Google account is not affected
- Anonymous analytics and crash report data held by Google (Firebase Analytics / Crashlytics) per [Google's retention policy](https://policies.google.com/privacy)

---

## Delete Your Account

The Focura app uses **Google Sign-In** for cloud sync. There is no separate Focura account — signing in links your progress data to your existing Google account.

**To remove your account from the app:**

1. Open the **Focura** app
2. Go to **Settings → Account**
3. Tap **Reset All Data** first (this removes your cloud data from our servers)
4. Then tap **Sign out**

Your progress data will be removed from our Firebase Firestore database. Your Google account itself is not deleted — only its association with the Focura app.

**If you need complete removal of all associated data**, contact us and we will manually delete any remaining records:

📧 [ictsimplified@gmail.com](mailto:ictsimplified@gmail.com?subject=Account%20Deletion%20Request%20–%20Focura)

Please include **"Account Deletion Request – Focura"** in the subject line. We will process your request within **7 days** and confirm by email.

---

## Data Summary

| Data | Deleted by Reset | Deleted on Sign-out | Retained |
|---|---|---|---|
| XP & progress (local) | ✅ | — | — |
| XP & progress (cloud) | ✅ | — | — |
| Firebase Analytics (anonymous) | — | — | Per Google policy |
| Firebase Crashlytics (anonymous) | — | — | Per Google policy |
| Google account | — | — | Not affected |

---

[← Back to Privacy Policy](/apps/focura/privacy)