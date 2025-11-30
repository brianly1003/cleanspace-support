# CleanSpace Privacy Policy

**Last Updated:** December 1, 2025

---

## Privacy-First Commitment

**CleanSpace is designed with privacy as a core principle.**

We don't request the "Ask App Not to Track" permission (App Tracking Transparency). We don't track you across other apps and websites.

---

## Our Approach to Privacy

CleanSpace protects what matters most: **Your personal content stays on your device.**

- Your photos never leave your device
- Your videos never leave your device
- Your contacts never leave your device
- Your files never leave your device

**What about advertising?** The free version uses Google AdMob to show ads. AdMob may collect device information and ad interaction data, but AdMob does NOT have access to your photos, videos, contacts, or files. Premium users have no ads and no AdMob SDK.

---

## What Data We Collect

### Your Personal Content: NONE

CleanSpace does NOT collect, upload, or share:

**Your Photos**
- Photos never leave your device
- All duplicate detection happens locally using on-device machine learning
- No photo uploads to our servers or third parties

**Your Videos**
- Videos stay on your device
- Video analysis (size, duration) happens locally
- No video uploads

**Your Contacts**
- Contact deduplication happens entirely on-device
- Contact data never leaves your device
- No contact uploads

**Your Files**
- Storage analysis happens locally
- File lists and storage data stay on your device
- No file information uploaded

**Your Personal Information**
- No name, email, phone number, or address
- No account required
- No login credentials

**Your Location**
- We don't request location permission
- We don't track where you use the app

---

### Advertising Data: LIMITED (Free Version Only)

**Free version users:** We use Google AdMob to display non-personalized advertisements. AdMob may collect:

**Device Information**
- Device model (e.g., iPhone 15 Pro)
- Operating system version (e.g., iOS 18.5)
- App version
- IP address (for general location, not precise GPS)

**Ad Interaction Data**
- Ad impressions (ads shown)
- Ad clicks
- Time spent viewing ads

**What AdMob does NOT collect:**
- Your photos, videos, or files
- Your contacts
- Your photo library contents or metadata
- Your storage breakdown
- Features you use within the app
- Your precise location (no GPS tracking)

**Premium version users:** The Premium version does not include the AdMob SDK. No advertising data is collected for Premium users.

**Technical implementation:** We use AdMob's non-personalized ads configuration, which means AdMob does not use data to build a profile of you across other apps and websites.

---

## How CleanSpace Works

### 1. Photo & Video Analysis (All Users)
- **Technology:** On-device machine learning
- **Processing:** All analysis happens locally on your device
- **Data Transfer:** Zero - photos and videos never leave your device
- **Cloud Storage:** None - all content stays local

**Examples of on-device processing:**
- Duplicate photo detection using local ML models
- Screenshot identification
- Large media scanning
- Video size calculation

### 2. Contact Deduplication (All Users)
- **Processing:** Happens entirely on-device using iOS Contacts framework
- **Data Transfer:** Zero - contacts never leave your device
- **Access:** Read-only (we don't modify contacts without your permission)

### 3. Storage Analysis (All Users)
- **Data Source:** iOS PhotoKit and FileManager frameworks
- **Processing:** Local calculation of storage usage
- **Reporting:** Displayed in-app only
- **Sharing:** Never - stays on your device

### 4. Private Photos Vault (All Users)
- **Encryption:** AES-256-GCM encryption
- **Key Storage:** iOS Secure Enclave on your device
- **Access Control:** Face ID/Touch ID + optional passcode
- **Cloud Upload:** Encrypted vault is NOT uploaded to our servers

**Note on iOS Backups:** If you have iCloud Backup enabled, iOS may backup your encrypted vault data to iCloud. This is a system-level feature we don't control. The vault remains encrypted in backups.

---

## Third-Party Services

### Google AdMob (Free Version Only)

**Purpose:** Display non-personalized advertisements in the free version of CleanSpace.

**What AdMob collects:**
- Device information (model, OS version, IP address)
- Ad interaction data (impressions, clicks, time spent)

**What AdMob does NOT collect:**
- Your photos, videos, contacts, or files
- Your app usage patterns
- Data from other apps (no cross-app tracking)

**How to avoid AdMob:** Upgrade to Premium ($6.99 one-time purchase). Premium users have no ads and no AdMob SDK installed.

**AdMob Privacy Policy:** https://policies.google.com/privacy

---

### Apple Frameworks (All Users)

We use Apple's native frameworks for core functionality:
- **PhotoKit** - Access and manage photo library
- **CryptoKit** - Encryption for Private Vault
- **SwiftUI** - User interface
- **Vision** - On-device image analysis for duplicate detection
- **Contacts** - Contact deduplication (with permission)

These frameworks operate entirely on your device and do not send data to Apple servers (except for Apple's standard system-level analytics, which you can disable in iOS Settings).

---

## Data Sharing

### Who We Share Your Data With:

**Your Personal Content:** NOBODY

We do NOT share your photos, videos, contacts, files, or personal information with anyone. This content never leaves your device.

**Advertising Data (Free Version Only):** Google AdMob

Free version users: Google AdMob receives device information and ad interaction data for the purpose of displaying non-personalized ads. Google does NOT receive your photos, videos, contacts, or files.

Premium version users: No data shared with AdMob (AdMob SDK is not included in Premium version).

**We do NOT share data with:**
- Data brokers or marketing companies
- Social media platforms
- Analytics companies (beyond AdMob's built-in ad analytics)
- Government agencies (unless legally required by valid court order)

---

## Your Rights

### Free Version Users

**Right to Access:**
- Your personal content (photos, videos, contacts, files) is stored locally on your device. You can access it anytime through iOS Settings.
- For advertising data collected by AdMob, you can submit a request to Google: https://support.google.com/My-Ad-Center-Help

**Right to Delete:**
- Your personal content: Delete the app to remove all local data
- AdMob data: Submit deletion request to Google

**Right to Opt-Out:**
- Upgrade to Premium to completely opt out of advertising data collection
- For iOS-level advertising preferences, go to Settings > Privacy > Apple Advertising

**Right to Export:**
- Your personal content stays on your device - no data to export from us
- For AdMob data: Contact Google

### Premium Version Users

Since Premium doesn't include AdMob and we don't collect your personal content:

- **Right to Access:** No data collected to access
- **Right to Delete:** No data collected to delete
- **Right to Opt-Out:** Already opted out (no ads, no AdMob)
- **Right to Export:** No data collected to export

---

## Data Retention

### Personal Content
**Retention Period:** Not applicable - we don't collect or store your photos, videos, contacts, or files on our servers.

### Advertising Data (Free Version Only)
**Retention Period:** Determined by Google AdMob. Typically 30-90 days for ad interaction data. See Google's privacy policy for details: https://policies.google.com/privacy/archive

---

## Children's Privacy (COPPA Compliance)

**Age Rating:** 4+ (No objectionable content)

**Children Under 13:**

CleanSpace does NOT knowingly collect personal information from children under 13:
- We don't collect photos, videos, or personal data from anyone (including children)
- **Free version with ads:** AdMob uses non-personalized ads which don't track or profile users, including children
- **Premium version:** No ads, no data collection

Parents can choose Premium version for additional peace of mind (no ads, no AdMob SDK).

If you believe a child under 13 has provided personal information, please contact us at privacy@cleanspace.app.

---

## App Permissions

CleanSpace requests the following iOS permissions:

### Photo Library Access (Required for core functionality)
- **Purpose:** Analyze and help you clean your photo library
- **Scope:** Read and delete photos (with your explicit permission per action)
- **Privacy:** Photos never leave your device
- **When requested:** When you first open the app

### Camera Access (Optional - for Private Vault)
- **Purpose:** Take photos for your encrypted vault
- **Privacy:** Photos encrypted immediately on-device with AES-256-GCM
- **When requested:** When you first use Private Vault feature

### Face ID / Touch ID (Optional)
- **Purpose:** Unlock the app and Private Vault securely
- **Privacy:** Biometric data stays in iOS Secure Enclave (never accessible to our app)
- **When requested:** When you enable app lock in Settings

### Notifications (Optional)
- **Purpose:** Subscription reminders and cleanup alerts (Premium users only)
- **Privacy:** Local notifications only, no data sent to servers
- **When requested:** After you install the app

### Contacts (Optional - for Contact Deduplication feature)
- **Purpose:** Find and help you merge duplicate contacts
- **Privacy:** Contacts processed on-device only, never uploaded
- **When requested:** When you first use Contact Deduplication feature

### Permissions We DON'T Request
- **Location** - Not needed or requested
- **Microphone** - Not needed or requested
- **App Tracking Transparency (ATT)** - Not requested (we don't do cross-app tracking)
- **Bluetooth** - Not needed or requested

---

## Security

### How We Protect Your Data

**On-Device Encryption:**
- Private Vault uses AES-256-GCM encryption (military-grade)
- Encryption keys stored in iOS Secure Enclave (hardware-protected)
- Biometric authentication (Face ID/Touch ID) for vault access

**Minimal Network Activity:**
- **Free version:** Network requests limited to AdMob ad delivery only
- **Premium version:** No network requests for app functionality
- Your photos, videos, contacts, and files never transmitted over network

**Code Security:**
- Native Swift code following Apple's security best practices
- Regular security reviews
- Minimal third-party dependencies (AdMob for free version only)

---

## App Store Privacy Label

### Free Version:
```
Data Not Linked to You
  The following data may be collected but is not linked to your identity:
  - Identifiers (Device ID for advertising)
  - Usage Data (Ad interactions)
  - Diagnostics (Ad performance data)

No Cross-App Tracking
  This app does not track you across apps and websites owned by
  other companies.

Note: Your photos, videos, contacts, and files are NOT collected.
Only advertising-related device data is collected by Google AdMob.
```

### Premium Version:
```
No Data Collected
  This app does not collect any data.

No Tracking
  This app does not track you across apps and websites owned by
  other companies.
```

---

## International Privacy Laws

### GDPR (European Union)

**Compliance Status:** Compliant

**Legal Basis for Processing:**
- Personal content: Not applicable (no processing on our servers)
- Advertising data (free version): Legitimate interest for ad-supported free version

**Your GDPR Rights:**
- Right to access, delete, and port advertising data: Contact Google AdMob
- Right to object: Upgrade to Premium to remove all advertising data collection
- Right to lodge complaint: Contact your local data protection authority

**Data Controller:**
- For personal content: Not applicable (processed locally on your device)
- For advertising data: Google LLC (see Google's GDPR compliance)

### CCPA (California)

**Compliance Status:** Compliant

**California Residents' Rights:**
- **Right to Know:** We don't collect your photos, videos, contacts, or files. AdMob collects device and ad data.
- **Right to Delete:** Upgrade to Premium or request deletion from Google AdMob
- **Right to Opt-Out of Sale:** We don't sell your data. AdMob doesn't sell data in CCPA terms.
- **Right to Non-Discrimination:** All features work the same for free and Premium users (except ads)

**Do Not Sell My Personal Information:** We don't sell personal information. Upgrade to Premium to remove all advertising data collection.

### Other Jurisdictions

We respect privacy laws in all jurisdictions. Our approach:
- Your personal content (photos, videos, contacts, files) stays on your device - no cross-border data transfer
- Advertising data (free version only) processed by Google AdMob according to Google's privacy policy
- Premium version collects no data from anyone, anywhere

---

## Changes to This Policy

We may update this privacy policy if our data practices change. If we make material changes:

1. Update the "Last Updated" date at the top
2. Notify you via in-app notification
3. For significant changes: Require you to review and accept the updated policy
4. Update our App Store Privacy Label
5. Provide at least 30 days notice before changes take effect

**How to stay informed:** Check this policy periodically at https://github.com/brianly1003/cleanspace-support/blob/main/PRIVACY_POLICY.md or contact us at privacy@cleanspace.app

---

## Contact Us

Have questions about privacy?

**Email:** privacy@cleanspace.app
**Support:** support@cleanspace.app

**Response Time:** Within 48 hours for privacy inquiries

---

## What Makes CleanSpace Different

**Most storage cleaner apps:**
- Track your usage patterns
- Upload photo metadata for analysis
- Use multiple advertising and analytics SDKs
- Collect extensive device and behavioral data

**CleanSpace:**
- Your photos, videos, contacts, and files stay on your device
- All analysis happens locally using on-device machine learning
- Free version: Only AdMob for non-personalized ads (no cross-app tracking)
- Premium version: Zero data collection, no ads, no tracking
- We don't request permission to track you across other apps

---

## Verification

Don't just trust us - verify!

**Free Version:**
1. Use network monitoring tools - you'll see only AdMob ad requests
2. Check App Store Privacy Label - only advertising data collected
3. Review this policy - we're transparent about AdMob usage

**Premium Version:**
1. Use network monitoring tools - zero network requests for app functionality
2. Check App Store Privacy Label - "No Data Collected"
3. iOS Settings > CleanSpace > No unusual permissions

**Both Versions:**
1. Check system permissions - only photo/camera access (no location, microphone, etc.)
2. Your photos never leave your device - verify with network monitoring
3. No "Ask App Not to Track" permission requested

---

**© 2025 CleanSpace. All rights reserved.**

*Your photos, videos, contacts, and files stay on your device. Always.*

---

## Version History

**v1.1 (December 1, 2025):**
- Updated policy URL to GitHub repository
- Minor formatting improvements

**v1.0 (October 28, 2025):**
- Initial privacy policy
- Disclosure of Google AdMob usage in free version
- Clear separation between free (with ads) and Premium (no ads) versions
