# Play Console Declarations Checklist

## App Info
- **Developer Name:** VK_Automata
- **Developer Contact Email:** vkanavitsados@gmail.com
- **Category:** Tools / Design / Productivity
- **Target Audience:** General / Everyone
- **App Access:** All features available. Premium features are locked behind an in-app purchase but no login is required.

## Monetization
- **Contains Ads:** Yes (for free users).
- **In-App Purchases:** Yes (One-time Premium to remove ads and unlock pro features such as LAB/LCH controls, Delta E comparison, and CxF export).

## Data Safety
- Ensure the Play Console Data Safety form is filled out using the `DATA_SAFETY_WORKSHEET.md` reference.
- Add Privacy Policy URL to the Play Console.

## Permissions
- `CAMERA`: Used strictly for the in-app camera capture functionality.
- `INTERNET`: Required for serving ads and validating Play Billing purchases.
- `AD_ID`: Required by the Google Mobile Ads SDK.
- **Note:** No broad storage access requested; uses Photo Picker and specialized MediaStore API.

## Testing Instructions for Reviewer
- **Photo Import:** Tap "Import Image" on the main screen to test Photo Picker.
- **Camera:** Tap "Camera" to test the capture workflow. It asks for permission only upon interaction.
- **Exporting:** Select a palette and use export options.
- **Premium:** Tap "Buy Premium" to launch the test purchase flow (use a licensed tester account).
- **Debug Features:** Any debug-only premium codes or logs are completely disabled/hidden in the release build.
