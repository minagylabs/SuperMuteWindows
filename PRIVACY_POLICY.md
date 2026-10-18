# Privacy Policy — Super Mute

**Last Updated**: September 10, 2026  
**Developer**: Minagy Labs (`minagylabs@gmail.com`)  
**Official Page**: [https://github.com/minagylabs/SuperMute](https://github.com/minagylabs/SuperMute)

---

## 1. Overview
Minagy Labs ("we", "our", or "us") built **Super Mute** (Android Application, `com.forcemute.app`) and the **Super Mute Shutter Helper** (Windows Companion Utility) as privacy-first utilities. We are deeply committed to protecting your personal information and device security.

**Our Core Privacy Principle is simple: We do not collect, store, transmit, or share any personal data whatsoever.**

---

## 2. Zero Data Collection & Storage
- **No Personal Data**: We do not collect names, email addresses, phone numbers, contacts, media, photos, or browsing history.
- **No Tracking or Analytics**: The application does not integrate third-party analytics SDKs (such as Firebase Analytics, Google Analytics, or Facebook Pixel).
- **No Advertising Networks**: Super Mute contains zero advertisements and zero ad-tracking beacons.
- **No Account Required**: The app runs immediately upon installation with no user account, registration, or login.

---

## 3. Device Permissions & System Settings
Super Mute only requests Android permissions strictly required to perform audio muting on device:

1. **Do Not Disturb Access (`ACCESS_NOTIFICATION_POLICY`)**:
   - *Purpose*: Used exclusively to engage and disengage device Do Not Disturb Total Silence (`INTERRUPTION_FILTER_NONE`) when muting.
2. **Audio Volume Management**:
   - *Purpose*: Used exclusively to read and set device audio stream levels (Media, Ring, Notification, System, Voice Call, DTMF, Bluetooth) to zero.
3. **Accessibility Service (`AccessibilityService`, Optional)**:
   - *Purpose*: Used solely to detect camera application launches for automatic temporary muting and to render the floating quick-toggle button on screen.
   - *Guarantee*: The Accessibility Service does not log keystrokes, inspect screen content, or read input fields.
4. **Samsung Camera Shutter Setting**:
   - *Purpose*: Modified via local USB debugging command to toggle Samsung Galaxy camera shutter silence.
   - *Guarantee*: Only this single specific system setting is queried and modified. No files are installed on the device.

---

## 4. Network Communications
- **Android App**: Does not require or use internet access. Operates 100% offline.
- **Windows Companion Tool**: Operates 100% offline via local USB connection. When the user explicitly clicks external support buttons, it opens the user's default browser to:
  - GitHub Issues: `https://github.com/minagylabs/SuperMute/issues`
  - Buy Me a Coffee: `https://buymeacoffee.com/minagylabs`
  - Instagram: `https://www.instagram.com/minagylabs/`

---

## 5. Security & The 10-Second Rule
When using the Windows Companion Tool with USB debugging:
- The tool only queries and toggles a single system setting key.
- Upon application exit, all local communication processes and ports are immediately terminated.
- We strongly recommend that users scan their computer with anti-virus software prior to use, and toggle USB debugging **OFF** immediately after muting their device.

---

## 6. Children's Privacy
Super Mute does not address anyone under the age of 13 and does not collect any personal identifiable information from children.

---

## 7. Contact Us
If you have any questions, suggestions, or concerns regarding this Privacy Policy, please contact us:
- **Email**: `minagylabs@gmail.com`
- **GitHub**: [https://github.com/minagylabs/SuperMute](https://github.com/minagylabs/SuperMute)
- **Instagram**: [https://www.instagram.com/minagylabs/](https://www.instagram.com/minagylabs/)
