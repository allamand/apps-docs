# FunEarner — Privacy Policy

_Last updated: 2 August 2026_

FunEarner ("we", "the app") is published by Sébastien Allamand. This policy describes what data the app processes and why.

## Summary

- **No account, no login, no tracking, no advertising.**
- **Self mode** keeps all data on your device.
- **Family mode** uses **Apple iCloud (CloudKit)** to sync rules and reward history between the parent's and the child's devices. Data is stored in the user's private iCloud, encrypted by Apple, and never accessible to the developer.
- Screen Time / device activity data is read **locally** to enforce the family rules you configure. It is never sent off-device by FunEarner.

## Data processed locally (both modes)

FunEarner uses Apple's **Family Controls / Screen Time (DeviceActivity, ManagedSettings)** framework:

- The app receives usage signals (which apps/categories are used and for how long) **from iOS itself, within a sandbox**.
- These signals are used only to unlock rewards ("fun screen time") and to apply the shields/limits you have chosen.
- The raw Screen Time data is **never read, exported or transmitted** by FunEarner. Apple's API deliberately hides identifying details from the app.

Data stored locally on the device:
- Rules and rewards you configure (app categories, time thresholds, amounts).
- Reward history (dates, amounts) for your own review.

## Self mode

All data stays on the device. FunEarner does not transmit anything over the network. Uninstalling the app erases everything.

## Family mode (iCloud sync)

When you enable Family mode, the parent's device creates a private CloudKit share and sends an invitation (QR code / link) to the child's device. Once the child accepts:

- Rules, reward history and activity summaries are synchronised between the two devices **through the users' own iCloud accounts** (CloudKit private/shared database).
- Data lives inside your iCloud. The developer has **no access** to it — CloudKit is end-to-end managed by Apple.
- We do not operate a backend server for FunEarner. There is no third party involved.

You can revoke the share at any time from the app or from iCloud settings. Revoking removes the child device from the shared data.

## Data we do NOT collect

- No name, email, phone number, address.
- No advertising identifier, no analytics SDK, no crash reporter with PII.
- No location.
- No contacts, no photos, no microphone, no camera.
- No data leaves the user's own iCloud.

## Children's privacy

FunEarner is designed for use by families. Because no personal data is transmitted to the developer or any third party, the app is compliant with COPPA (US) and GDPR-K (EU) by design. Parents remain in full control via Screen Time and Family Sharing.

## Third parties

FunEarner does not use third-party analytics, advertising or tracking SDKs.

The app relies on Apple system services (Family Controls, CloudKit, iCloud Keychain) which are governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Your rights (GDPR)

Because we do not hold any personal data on our servers, there is nothing to export or delete on our side. You can:

- Delete all local data by uninstalling the app.
- Delete Family-mode data by revoking the iCloud share and uninstalling the app on all devices.
- Contact us if you have any question: [itunes@allamand.com](mailto:itunes@allamand.com).
