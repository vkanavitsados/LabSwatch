# Data Safety Worksheet

This worksheet helps answer the Google Play Console Data Safety questionnaire.

## 1. Data Collection and Security
- **Does your app collect or share any of the required user data types?** Yes.
- **Is all of the user data collected by your app encrypted in transit?** Yes (Data transmitted by AdMob and Play Billing is encrypted).
- **Do you provide a way for users to request that their data be deleted?** Yes (Users can delete palettes manually; no account data exists).

## 2. Data Types
### App Activity
- **App interactions:** Collected by AdMob (Optional, for analytics/advertising).
- **Crash logs / Diagnostics:** Collected by Google Play Services / AdMob.

### Device or other identifiers
- **Device or other IDs:** Collected by AdMob (Required for ads functionality). Shared with third parties (advertisers).

### Photos and Videos
- **Photos:** The app processes photos locally via Photo Picker and Camera. **Not uploaded or shared off-device by the app.**

### Financial Info
- **Purchase History:** Handled entirely by Google Play Billing. The app only checks entitlement status.

## 3. Third-Party SDKs
- **Google AdMob:** May collect IP address, advertising ID, app interactions, and crash logs.
- **Google Play Billing:** Handles transactions and purchase verification securely.
