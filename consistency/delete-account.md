---
layout: page
title: Delete Account & Data — Consistency
permalink: /consistency/delete-account
app_name : Consistency
app_icon : assets/apps/consistency/icon.png
app_url  : /consistency
include_in_header: false
---

# Delete Account & Data

**App:** Consistency – Habit Tracker
**Developer:** ICT Solved!

---

## Delete All Your Data (Without Deleting Your Account)

You can delete all habit and completion data directly inside the app at any time, without deleting your Google account or contacting us.

**Steps:**

1. Open the **Consistency** app
2. Tap the **Settings** icon in the top app bar
3. Scroll to the **Data** section
4. Tap **Reset all data**
5. Confirm when prompted

**What gets deleted:**
- All habits and their configurations
- All completion history
- All reminder schedules
- If you are signed in, your cloud-synced data is also deleted from Firebase Firestore

**What is retained:**
- Your Google account is not affected
- Anonymous analytics and crash report data held by Google (Firebase Analytics / Crashlytics) per [Google's retention policy](https://policies.google.com/privacy)

---

## Delete Your Account

The Consistency app uses **Google Sign-In** for cloud sync. There is no separate Consistency account — signing in links your habit data to your existing Google account.

**To remove your account from the app:**

1. Open the **Consistency** app
2. Go to **Settings → Account & Sync**
3. Tap **Reset all data** first (this removes your cloud data from our servers)
4. Then tap **Sign out**

Your habit data will be removed from our Firebase Firestore database. Your Google account itself is not deleted — only its association with the Consistency app.

**If you need complete removal of all associated data**, contact us and we will manually delete any remaining records:

📧 [ictsimplified@gmail.com](mailto:ictsimplified@gmail.com?subject=Account%20Deletion%20Request%20–%20Consistency)

Please include **"Account Deletion Request – Consistency"** in the subject line. We will process your request within **7 days** and confirm by email.

---

## Data Summary

| Data | Deleted by Reset | Deleted on Sign-out | Retained |
|---|---|---|---|
| Habits & history (local) | ✅ | — | — |
| Habits & history (cloud) | ✅ | — | — |
| Firebase Analytics (anonymous) | — | — | Per Google policy |
| Firebase Crashlytics (anonymous) | — | — | Per Google policy |
| Google account | — | — | Not affected |

---

[← Back to Privacy Policy](/apps/consistency/privacy)
