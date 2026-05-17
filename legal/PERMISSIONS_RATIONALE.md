# Permissions Rationale

## CAMERA
**Why we need it:** To allow users to capture live images directly within the app for color sampling.
**When it's requested:** Only when the user taps the "Camera" button.

## INTERNET
**Why we need it:** 
- To load and display ads from Google AdMob for free users.
- To communicate with Google Play to verify and process Premium purchases.
**When it's requested:** Granted automatically at install time.

## AD_ID (com.google.android.gms.permission.AD_ID)
**Why we need it:** Required by the Google Mobile Ads SDK for serving relevant ads and frequency capping.
**When it's requested:** Granted automatically at install time (subject to user opt-out in device settings).

## Storage (Not broadly requested)
**Why we don't need it:** We use the Android Photo Picker to let users select specific images without granting access to their entire gallery. Saved photos are placed in the public `Pictures/LabSwatch` directory using modern Android `MediaStore` APIs.
