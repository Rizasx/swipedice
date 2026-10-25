Swipe Dice - Android project (WebView app, works offline)

Build the APK, pick one:

A) Android Studio: File > Open this folder, wait for sync,
   Build > Build APK(s). The file lands in app/build/outputs/apk/debug/app-debug.apk

B) Command line (needs JDK 17, the Android SDK and Gradle 8.7):
   gradle assembleDebug

C) GitHub: push this folder to a repo. The Build APK action runs on every push.
   Open the run and download "SwipeDice-debug-apk" under Artifacts.

To change the game: edit app/src/main/assets/index.html.
App id is com.swipedice.app (app/build.gradle). Change it before a Play Store upload.
The debug APK installs on any phone (allow installs from unknown sources).
For Google Play you need a signed release build (Build > Generate Signed Bundle).
