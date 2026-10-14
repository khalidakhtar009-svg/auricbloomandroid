AURIC BLOOM Android App Project (source)
========================================

This is an Android Studio project wrapping the existing AURIC BLOOM storefront prototype in an Android app shell. It is NOT a compiled APK yet.

Included:
- Android launcher app named AURIC BLOOM
- Store and Admin navigation buttons
- Storefront, admin dashboard, logo, manifest and service worker bundled as local assets
- WhatsApp order links using +91 6301984703

Build an APK:
1. Install Android Studio on a computer: https://developer.android.com/studio
2. Extract this project ZIP.
3. In Android Studio choose Open, then select the AuricBloom folder.
4. Allow Gradle sync and install Android SDK Platform 35 if prompted.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. The debug APK will be created at app/build/outputs/apk/debug/app-debug.apk.
7. Transfer the APK to your Android phone, allow installing from that source when prompted, and install it.

Important limitations:
- This is a local prototype. Storefront and admin data are not connected to a shared online database.
- Product price/catalog editing is browser/local storage only; this does not yet sync between the customer store and admin dashboard.
- No live payment gateway, secure admin authentication, production customer accounts, loyalty engine, shipping integration or real order tracking.
- Do not use this prototype to collect payment details or sensitive customer data.
- Before public release, test on devices, add secure backend/services, privacy and commerce policies, and create a signed release APK.
