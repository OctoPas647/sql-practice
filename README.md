# SQL Practice

- **Live link:** https://claude.ai/artifact/B4U9g8NfBjbEKbTsKMXDrg
- **Android app:** `app.sqlpractice`, latest build v1.3.2

## What's in here

| Path | What it is |
|---|---|
| `index.html`, `alasql.min.js`, `war-thunder-kill.wav` | The app itself (v1.3.2, taken from `SQLPractice-1.3.2.apk`). Open `index.html` in a browser to run it. |
| `android/` | Android Studio project that wraps the app into an APK. Its `app/src/main/assets/` holds the same v1.3.2 files. |

Note: the published claude.ai link is an older version (91 KB) than the APK (135 KB).
The Kotlin code in `android/` comes from the original Android project (version 1.0);
the 1.3.2 build's own Kotlin source wasn't saved on this PC, only the compiled APK.

## How to edit
Open this folder in Claude Code and ask for changes. Change `index.html` here, then copy it
into `android/app/src/main/assets/` before building a new APK (see `android/README.md`).
