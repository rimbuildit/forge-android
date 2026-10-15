FORGE — PHONE-ONLY ANDROID APK BUILDER

This is an Android Studio/Gradle project, NOT the APK itself. It is configured to build an installable Android APK using GitHub Actions in the cloud, so you do not need a computer.

PHONE-ONLY STEPS
1. Download this ZIP and extract it with your phone's Files app.
2. In Chrome, sign in to GitHub and create a NEW repository. Keep it private if you prefer.
3. Upload the CONTENTS of this extracted folder into the repository root (not the enclosing folder). Ensure .github/workflows/build-apk.yml is uploaded too. If the GitHub mobile upload flow hides dot-folders or makes this difficult, use Chrome's Desktop site option.
4. Open the repository's Actions tab. If prompted, enable Actions.
5. Select “Build FORGE APK” on the left and tap “Run workflow”. If it already ran after the upload, open the latest run instead.
6. Wait for the run to finish with a green check. Scroll to Artifacts and download “FORGE-Android-APK”. This downloads another ZIP.
7. Extract that ZIP. Tap app-debug.apk to install. If Android blocks it, allow “Install unknown apps” for the browser/files app you used, then retry. Only install the APK you built from your own repository.

The installed app wraps the existing FORGE HTML locally in Android WebView and enables JavaScript + localStorage. Your old browser data does not automatically move into the APK; export/backup it from the old version first if you need it.

If GitHub mobile upload is awkward, tell ChatGPT which screen you are stuck on and share a screenshot.
