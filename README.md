# Cockroach Library Android App (Live Web Wrapper)

This Android app wraps **https://01.cockroachlibrary.workers.dev/** into a standalone, full-screen Android application.

## Features
- **Live Web Engine:** Loads `https://01.cockroachlibrary.workers.dev/` with JavaScript, DOM storage, and persistent cookies enabled.
- **Smart Link Routing:** Keeps all Cockroach Library pages inside the app, while opening Google Meet rooms and external contact links in their native apps.
- **Pull-to-Refresh & Native Back Button:** Swipe down at the top to reload and navigate back cleanly.

## Build the APK via GitHub Actions
1. Create a new empty repository on GitHub (e.g., `cockroach-library-app`).
2. Extract `CockroachLibraryApp.zip` and push all files to `main`.
3. Open the **Actions** tab, wait for **Build Cockroach Library APK** to finish, and download **CockroachLibrary-APK** from **Artifacts**.
