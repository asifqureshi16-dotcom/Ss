SS FRUITS BHOPAL — Android Studio starter project

STATUS: Source project only. NOT a compiled APK or AAB and NOT published.

Open the folder in Android Studio with JDK 17 and Android SDK 36 installed.
Wait for Gradle sync. Test on a real Android phone.
Build > Generate Signed App Bundle / APK > Android App Bundle.
Keep the signing keystore and passwords safe. Never share them in chat.

IMPORTANT BEFORE PLAY STORE:
- This is a starter WebView wrapper, not a production-validated app.
- The HTML currently stores business data in browser localStorage. No Supabase
  cloud sync or verified account-based backup is implemented in this project.
- Data in the old Chrome website will NOT automatically appear in this app.
- Export backups from the old app before moving data; confirm import/export works.
- The HTML references icons/manifest not present in the upload; those are not needed
  for this native wrapper, but the launcher icon is currently Android default.
- Verify A6 printing, bill creation, ledger, reports, and backup on-device.
- The HTML's backup download/import may not work in WebView without additional
  Android integration. Do NOT use for real customer records until tested.
- Add privacy policy, app icon, store listing, screenshots, Data safety details.
- Ensure meaningful native functionality and comply with Google Play quality policy.
- Play Console registration, testing and Google review are still required.
