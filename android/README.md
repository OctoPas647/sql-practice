# SQL Practice for Android

## Build the app
1. Install Android Studio (free): https://developer.android.com/studio
2. Unzip this folder, then in Android Studio choose File > Open and pick the `SQLPractice` folder.
   Wait for the Gradle sync to finish; it downloads what it needs the first time.
   If it offers to upgrade Gradle or the Android Gradle plugin, accepting is fine.
3. Build > Build App Bundle(s) / APK(s) > Build APK(s).
   When it finishes, click "locate". The file is `app-debug.apk`.

## Install it on your phone
Either:
- Plug the phone in with USB debugging on (Settings > About phone > tap "Build number" 7 times,
  then Settings > Developer options > USB debugging) and press the green Run button, or
- Copy `app-debug.apk` to the phone, open it, and allow "Install unknown apps" when asked.

## Offline use
The SQL engine (AlaSQL) loads from the internet the first time and is cached after that.
To make the app work fully offline from the start, download
https://cdn.jsdelivr.net/npm/alasql@4.4.0/dist/alasql.min.js
and put it in `app/src/main/assets/` next to `index.html`, then rebuild.

## Notes
- Points and progress are saved on the phone.
- "Ask Claude what's wrong" only works on the claude.ai version, so it's hidden in the app.
  The step-by-step Help hints all work.
