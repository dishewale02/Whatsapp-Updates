# Work Updates (Android)

WebView wrapper around index.html, with the client list in assets/clients.js.

## Get an installable APK
Option A - Android Studio: open this folder, let Gradle sync, Build > Build APK(s).
  APK: app/build/outputs/apk/debug/app-debug.apk

Option B - no install needed: upload this folder to a new GitHub repository.
  The Build APK workflow runs automatically (Actions tab); download the
  WorkUpdates-apk artifact, unzip it, and copy app-debug.apk to your phone.

## Install on phone
Open the APK on the phone and allow "Install unknown apps" when asked.
