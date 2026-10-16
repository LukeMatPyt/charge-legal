---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**App:** Charge: Subscription Tracker ("Charge")
**Effective date:** 16 October 2026
**Last updated:** 16 October 2026

## 1. Who we are

Charge ("we", "us", "the App") is an app for iPhone, iPad and Mac developed and operated by an individual developer based in Poland (the "Developer"). Contact: **radioideaxp@gmail.com**.

For the purposes of the EU General Data Protection Regulation (GDPR), the Developer is the **Data Controller** for the limited categories of personal data described below.

## 2. TL;DR

- Charge has **no accounts and no backend**. The subscriptions you track stay **on your device** and, if you use iCloud, in **your own private iCloud database** — we cannot see them.
- Reminders are **local notifications** scheduled by iOS on your device. Nothing about them is sent to us.
- Payments for Charge Pro are processed by **Apple**. We use **RevenueCat** to check whether your Pro subscription is active; it receives a pseudonymous ID and purchase events, never the subscriptions you track.
- **No advertising, no analytics, no tracking.** We do not use the advertising identifier (IDFA) and never show the tracking prompt.

## 3. Data we process

### 3.1 Data that stays with you (on your device and in your iCloud)

| Data | Purpose | Where it is stored |
|---|---|---|
| Subscriptions you add (name, amount, billing cycle, next payment date, reminder setting, color, Home/Work list, free-trial dates) | Show your spending, upcoming payments and reminders | On your device. If iCloud is enabled for Charge, also in **your private CloudKit database** so your iPhone, iPad and Mac stay in sync |
| Payment history (past charges recorded by the App) | Spending history | Same as above |
| App settings (currency, default reminder, selected list) | App configuration | On your device |
| App-lock PIN | Optional lock screen | On your device only, stored as a **salted one-way hash** in the iOS Keychain. The PIN itself is never stored or sent anywhere |

Data in your private iCloud database is protected by Apple and belongs to your Apple ID. **We have no access to it** and cannot read, export or recover it.

The home-screen widget reads the same on-device data; it does not send anything off the device.

### 3.2 Data processed by Apple (App Store / StoreKit)

When you buy Charge Pro:

- Apple processes your payment, Apple ID and billing information **directly**.
- We do **not** receive your name, email address, payment method or Apple ID.
- Apple's practices are governed by the [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

### 3.3 Data processed by RevenueCat (subscription status)

We use **RevenueCat, Inc.** (USA) as a service provider / data processor to verify and manage the status of Charge Pro. RevenueCat receives:

- A **pseudonymous app user ID** (randomly generated — not your name, email or Apple ID)
- **Purchase events** from the App Store (product, transaction date, price, currency, storefront country)
- **Device and app metadata** (OS version, app version, language, country)
- **Subscription status** (active, expired, in grace period, billing retry)

RevenueCat does **not** receive the subscriptions you track, their amounts, your payment history or your PIN.

- Role: **Data Processor** acting on our instructions under RevenueCat's Data Processing Agreement.
- Transfers outside the EEA rely on the **EU Standard Contractual Clauses (SCCs)**.
- RevenueCat's privacy policy: <https://www.revenuecat.com/privacy>.

### 3.4 Data we do NOT collect

We do **not** collect, store or process:

- Your name, email address, phone number or postal address
- Bank, card or account details — Charge never connects to your bank; you enter subscriptions yourself
- Contacts, photos, location, microphone, camera or health data
- The advertising identifier (IDFA)
- Analytics, crash reports or telemetry from third-party SDKs (no Firebase, Mixpanel, Sentry, Google Analytics or similar)
- Any cross-app or cross-site tracking data

## 4. Permissions the App requests

| iOS permission | Why we ask | Required? |
|---|---|---|
| **Notifications** | To remind you before a subscription renews and the day before a free trial turns paid, at 10 am local time | Optional. Charge works without it; you just won't get reminders |

You can change this at any time in **iOS Settings → Charge → Notifications**.

## 5. Legal basis for processing (GDPR Art. 6)

| Processing | Legal basis |
|---|---|
| Operating the App on your device and syncing via your iCloud | **Performance of a contract** (Art. 6(1)(b)) |
| Managing Charge Pro via RevenueCat | **Performance of a contract** (Art. 6(1)(b)) |
| Sending reminder notifications | **Consent** (Art. 6(1)(a)) — the notifications permission |
| Accounting and App Store compliance | **Legal obligation** (Art. 6(1)(c)) and **legitimate interests** (Art. 6(1)(f)) |

## 6. Data retention

- **On-device data:** kept while the App is installed. Deleting a subscription with **Delete forever** removes it and its history. Deleting the App removes its on-device data.
- **iCloud data:** kept in your private iCloud database until you delete it. You can remove it in **iOS Settings → [your name] → iCloud → Manage Account Storage → Charge → Delete Data**.
- **RevenueCat:** keeps subscription records as needed to manage your entitlement and for accounting/audit obligations.
- **Apple:** keeps transaction history under Apple's Privacy Policy.

## 7. Your rights under GDPR

If you are in the EEA, the UK or Switzerland, you have the right to:

- **Access** the data we hold about you (Art. 15)
- **Rectify** inaccurate data (Art. 16)
- **Erase** your data (Art. 17)
- **Restrict** processing (Art. 18)
- **Data portability** (Art. 20)
- **Object** to processing based on legitimate interests (Art. 21)
- **Withdraw consent** at any time (Art. 7(3))
- **Lodge a complaint** with your supervisory authority. In Poland this is the **President of the Personal Data Protection Office (UODO)**, <https://uodo.gov.pl>.

The data you track in Charge is under your control on your device and in your iCloud, so you can view, change or delete it directly. For data held by RevenueCat, email **radioideaxp@gmail.com**. Because we do not know who you are, please include the **order ID** from your Apple purchase receipt (found in your email from Apple or at <https://reportaproblem.apple.com>) so we can locate the record.

We will respond within **30 days** (GDPR Art. 12(3)).

## 8. Your rights under CCPA (California residents)

We do **not** sell or share personal information as defined by the CCPA. California residents have the access, deletion and correction rights described above and may send requests to **radioideaxp@gmail.com**.

## 9. Children

Charge is **not intended for children under 13** (or under 16 in the EEA where local law sets a higher age of digital consent). We do not knowingly collect data from children. If you believe a child has bought Charge Pro, contact us and we will delete any related data RevenueCat holds.

## 10. International data transfers

Your tracked subscriptions do not leave your device except to sync with your own iCloud account (Apple). The only transfer we initiate is the pseudonymous identifier and purchase metadata sent to **RevenueCat in the United States**, covered by the EU Standard Contractual Clauses.

## 11. Security

We rely on:

- **iOS app sandboxing** and **Data Protection** (file-level encryption) for on-device data
- **iCloud / CloudKit** security for synced data
- The **iOS Keychain** for the salted PIN hash
- **HTTPS / TLS** for the connection to RevenueCat
- **Apple's StoreKit** for all payments (we never see card data)

No method of storage or transmission is 100% secure; we cannot guarantee absolute security.

## 12. Changes to this policy

We may update this policy. The "Last updated" date above will change, and material changes will be announced in the App. Continuing to use the App after a change means you accept the updated policy.

## 13. Contact

**radioideaxp@gmail.com**

Developer based in Poland. Supervisory authority: UODO (Poland).
