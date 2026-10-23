# Privacy Policy for ScanQ - QR & Barcode Scanner

**Effective Date:** October 24, 2026  
**Last Updated:** October 24, 2026  
**Developer / Publisher:** DuhaLab (Duha Lab)  
**Contact Email:** support@duhalab.com

Welcome to **ScanQ - QR & Barcode Scanner** ("we," "our," or "the App"). This Privacy Policy explains how we handle information when you use the App.

We are committed to a privacy-first approach. The App is designed to work without creating user accounts, without collecting personal data, and without sending your private information to our servers.

## Get the App on Google Play

Download ScanQ — QR Code & Barcode Scanner from Google Play:

https://play.google.com/store/apps/details?id=com.duhalab.scanq

---

## 1. Overview

**ScanQ does not collect, store, transmit, or share your personal information with us or with any third party for marketing purposes.**

- **No account required:** You do not need to create an account, sign in, or provide personal details such as your name, email address, or phone number.
- **Local-only processing:** QR and barcode scanning, code generation, scan history, favorites, and app settings are processed and stored locally on your device.
- **No backend user database:** We do not operate a server that stores your scan history, generated QR data, app configuration, or personal information.
- **User-controlled data:** Any data you manually enter to generate a QR code (for example, contact details, Wi‑Fi information, event details, or other text) remains strictly on your device unless you choose to save, share, or export it yourself.

---

## 2. Permissions Used by the App

ScanQ requests only the minimum permissions necessary for its core features. We do not request broad access to your personal data, contacts, media library, location, microphone, or call logs.

### 2.1 Camera Permission (`android.permission.CAMERA`)

- **Purpose:** Used to capture live camera frames so the App can detect and decode QR codes and barcodes.
- **Data Handling:** Camera frames are processed locally on your device in real-time. They are never recorded, uploaded, stored, or transmitted to us or any third-party server.

### 2.2 Photo / Gallery Access (Android System Photo Picker)

- **Purpose:** If you choose to scan a QR code from an existing image, the App uses Android's built-in, privacy-preserving Photo Picker.
- **Data Handling:** The App receives access only to the single image you explicitly select. It does not browse, read, upload, or analyze your entire photo library.
- **Policy compliance:** The App does not request broad photo/media permissions such as `READ_EXTERNAL_STORAGE` or `READ_MEDIA_IMAGES`.

### 2.3 Phone Call Permission (`android.permission.CALL_PHONE`)

- **Purpose:** If you scan a QR code containing a phone number and choose the "Call" action, the App can initiate the call via your device dialer.
- **Data Handling:** The App does not access your call logs, contacts, SMS, or other personal communication data.

### 2.4 Wi‑Fi Access

- **Purpose:** If you scan a Wi‑Fi QR code and choose to connect to the network, the App uses standard Android Wi‑Fi APIs.
- **Data Handling:** Wi‑Fi credentials are used solely to establish connection with the selected network and are never transmitted to our servers.

### 2.5 Vibration (`android.permission.VIBRATE`)

- **Purpose:** Provides haptic feedback after a successful scan.

### 2.6 Notification Permission (`android.permission.POST_NOTIFICATIONS`)

- **Purpose:** On Android 13 (API level 33) and higher, this permission allows the App to deliver notifications (such as app update notices, feature alerts, and announcements).
- **Control:** You can grant, deny, or revoke this permission at any time in your device settings.

### 2.7 No Unnecessary Permissions

The App does not request unnecessary permissions such as access to your contacts, microphone, SMS, call logs, precise location data, or broad media access for advertising or cross-app tracking.

---

## 3. Local Data Storage

ScanQ stores the following information locally on your device only, using standard on-device storage (such as SQLite or SharedPreferences):

| Data Type | Purpose | Where It's Stored |
|---|---|---|
| Scan History | Review previously scanned QR codes and barcodes | On-device only |
| Favorites | Quickly access frequently used scans | On-device only |
| Generated QR Content | Store QR content you create (such as contact details, event information, Wi‑Fi credentials) | On-device only |
| App Settings | Language, theme, sound, vibration, flashlight, and scan preferences | On-device only |

This information is never transmitted to us or to third parties unless you manually choose to share a generated code or open an external link.

You can delete this data at any time from the App's Settings screen or by clearing the App data / uninstalling the App.

---

## 4. QR Code Generation and Sensitive Information

When you use the "Create" feature to generate a QR code (for example, a Wi‑Fi network password, vCard, business card, or event details), the information you enter is used only to generate the QR code image locally.

This information:

- Is never sent to ScanQ, Duha Lab, or any third-party server;
- Remains on your device unless you choose to save or share the QR image yourself;
- Is your responsibility to protect once shared — anyone who scans the generated QR code can read its contents.

---

## 5. Third-Party Services and Firebase

ScanQ is designed with a privacy-first approach. We do not sell, rent, or trade your personal information.

To support critical app infrastructure, ScanQ integrates with:

### 5.1 Firebase Cloud Messaging (Google LLC)

- **Purpose:** We use Firebase Cloud Messaging (FCM) to deliver push notifications, such as major app update notifications, important announcements, and feature releases.
- **Information Processed:** To deliver notifications, Firebase uses an automatically generated, anonymous device registration token (FCM Token). This token is a random technical identifier that allows Google servers to route notifications to your specific device.
- **Privacy Safeguards:**
  - FCM tokens are not linked to any personal identifying information (e.g., your name, email address, phone number, or scan history).
  - No scanning data or generated QR codes are ever shared with or accessible to Firebase.
  - You can completely disable notifications at any time through your device's system settings (`Settings > Apps > ScanQ > Notifications`).
- For more information on how Google handles data in Firebase, please review [Google's Privacy Policy](https://policies.google.com/privacy) and [Firebase Data Privacy and Security](https://firebase.google.com/support/privacy).

### 5.2 External Links

Any web links (URLs) contained inside scanned QR codes or barcodes are opened only when you explicitly tap to open them in your default web browser. Once you leave the App, the privacy policy of the visited website governs your data.

---

## 6. Data Sharing and Disclosure

Because ScanQ does not collect or transmit your personal data to our servers:

- We do not sell, rent, trade, or monetize your personal information.
- We do not share personal data with data brokers, advertisers, or marketing networks.
- We do not maintain user accounts or personal profiles.

We only disclose information if strictly required by law, such as to comply with a valid subpoena, court order, or governmental authority.

---

## 7. Children's Privacy

ScanQ does not knowingly collect or solicit personal information from children under the age of 13 (or under the applicable age of digital consent in your jurisdiction).

Because the App does not collect personal data from any user, it is designed to comply with applicable privacy requirements, including the Children’s Online Privacy Protection Act (COPPA) and the General Data Protection Regulation (GDPR).

---

## 8. Security

We value your trust. Because your scan history and generated codes remain on your device and are not stored on our servers, the security of your local data relies on your device's operating system security features (such as screen locks, biometric authentication, and app sandboxing).

We follow best practices to minimize data processing and keep your data strictly on-device.

---

## 9. International Users and Data Transfers

ScanQ is available globally. The App's core functionality runs entirely on your device. For notification delivery through Firebase Cloud Messaging, technical transmission tokens may be processed on Google servers located in the United States and other jurisdictions where Google operates data centers, in accordance with Google's robust security and privacy certifications.

---

## 10. Your Rights and Choices

- **Access and Review:** All scan history, favorites, and generated items are immediately accessible to you inside the App.
- **Deletion:** You can delete individual items, clear all history with a single tap in Settings, or uninstall the App to permanently remove all stored data from your device.
- **Permissions Control:** You can revoke Camera, Notification, or other permissions at any time through your Android System Settings (`Settings > Apps > ScanQ > Permissions`).

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect updates in the App's functionality, relevant laws, or privacy practices. Any changes will be posted with an updated "Last Updated" date at the top of this document.

We encourage you to review this Privacy Policy periodically. Your continued use of the App following the posting of changes signifies your acceptance of the revised policy.

---

## 12. Contact Us

If you have any questions, feedback, or inquiries regarding this Privacy Policy or ScanQ's privacy practices, please contact us at:

- **Developer / Publisher:** DuhaLab (Duha Lab)
- **Email:** support@duhalab.com

---

*© 2026 DuhaLab. All rights reserved.*

# ScanQ — QR Code & Barcode Scanner
[![Google Play](https://img.shields.io/badge/Google_Play-Download-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.duhalab.scanq)
[![Version](https://img.shields.io/badge/Version-2.1.0-blue?style=for-the-badge)](https://play.google.com/store/apps/details?id=com.duhalab.scanq)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
**Download the app from Google Play:**  
👉 **[ScanQ on Google Play](https://play.google.com/store/apps/details?id=com.duhalab.scanq)**
