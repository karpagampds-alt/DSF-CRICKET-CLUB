# DSF CRICKET CLUB  - Android project

## Build the APK (Android Studio)
1. Install Android Studio (free): https://developer.android.com/studio
2. File > Open > select this folder. Let Gradle sync finish (first time downloads SDK pieces).
3. Plug in a phone (USB debugging on) and press Run, or:
   Build > Build Bundle(s)/APK(s) > Build APK(s)
4. APK: app/build/outputs/apk/debug/app-debug.apk -> copy to phone and install.

## Notes
- The app is your HTML, unchanged except Share Image / PDF now open Android's share sheet.
- Match data and player photos are stored on the device (localStorage).
- To edit later, change app/src/main/assets/index.html and rebuild.
- Play Store: Build > Generate Signed Bundle (AAB).
