Simulator Rx-9 - Android APK builder

This project builds an installable Android APK automatically using GitHub Actions.
1) Upload the CONTENTS of this folder to the root of your GitHub repository (not this ZIP).
2) Open the repository's Actions tab and select "Build Simulator Rx-9 APK".
3) Tap "Run workflow" if it did not start automatically after upload.
4) When the green check appears, open that workflow run and download the artifact named "Simulator-Rx-9-APK".
5) Extract the downloaded artifact ZIP; install app-debug.apk on your Android phone.
GitHub Actions is used because this workspace does not have the Android SDK installed to compile a signed APK locally.
