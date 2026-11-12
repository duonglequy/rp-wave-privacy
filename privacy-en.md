# Privacy Policy – R&P Wave

Last updated: 12 November 2026

R&P Wave (the "app") is an internal app of R&P Electronics Company Limited (the "company", "we") for its Board of Directors: ERP figures, approval of documents and notifications. It is not offered to customers or the public; only people with an ERP account issued by the company can sign in.

## 1. Data we process

| Data | Purpose |
|---|---|
| ERP account (user name, full name, role and rights) and the one-time passcode (OTP) | Sign-in, and deciding what you may see and approve |
| A device identifier created by the app, device type (iOS/Android), app version | Managing signed-in devices, revoking a device |
| Push registration token (FCM/APNs) | Delivering approval requests and alerts |
| IP address and time of access | Security and access logs of the ERP |
| Your approve/reject decisions with notes | Recorded on the document in the ERP |

Business figures (revenue, estimated gross margin, supplier quotes, documents waiting for approval) belong to the company and are shown on screen according to your rights. The app **does not store** cost figures, quotes or quote files on the device. It blocks screenshots and screen recording, and hides its preview in the recent-apps list.

Face ID / fingerprint / device passcode is handled by the operating system only, to unlock the app and to confirm approval decisions; the app never receives biometric data.

We do **not** collect location, contacts, photos, microphone or camera data. The app has no advertising, no third-party tracking or analytics, and we do not sell or share data for marketing.

## 2. Where the data lives

- ERP data is on the company's servers in the AWS Singapore region (ap-southeast-1) and travels over encrypted HTTPS.
- Google Firebase Cloud Messaging (FCM) and the Apple Push Notification service (APNs) are used only to deliver notifications to the device. Notification text is kept short; the push token is passed to these services as the operating system requires.
- On the device we keep only the sign-in session token (in the iOS Keychain or the Android keystore) and display choices (language, light/dark).

## 3. Retention

- Session and device identifier: until you sign out, the company revokes the device or the session expires.
- Push token: removed from the server when you sign out or the device is revoked, or when the push service reports it invalid.
- Access logs (IP, time): kept under the company's security policy to investigate incidents, for at most 12 months.
- Documents and approval decisions are business and accounting records of the company, kept as accounting law requires.

## 4. Your choices and deletion

- Signing out in the app (Settings) removes the session and push token of that device, on the device and on the server.
- Administrators can revoke any device or lock an account at any time.
- ERP accounts are managed by the company and cannot be created in the app. To have an account changed or deleted, or to ask what we hold about you, write to admin@rpc.vn; we reply within 30 days. Some records (for example documents you approved) must be kept by law.
- The "Try it" demo mode uses sample data inside the app, needs no account and sends nothing to a server.

## 5. Children

The app is for managers of the company and is not directed at anyone under 18.

## 6. Changes

If this policy changes we update this page and the "Last updated" date.

## 7. Contact

R&P Electronics Company Limited
Email: admin@rpc.vn · Website: https://www.rpc.vn
