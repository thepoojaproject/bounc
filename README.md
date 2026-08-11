# BounceX — Android APK

The original BounceX HTML game is bundled locally into an Android app.

## GitHub APK build

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Commit to `main`.
4. Open **Actions**.
5. Select **Build BounceX APK**.
6. Click **Run workflow** if it did not start automatically.
7. After the green check, open the workflow run.
8. Download **BounceX-debug-apk** from Artifacts.
9. Extract it and install `app-debug.apk` on Android.

This version uses:
- Android Gradle Plugin 8.7.3
- Gradle 8.9
- JDK 17
- compileSdk 35
- No external AndroidX dependencies
- Local HTML asset; no internet/server required for the game

The Node 20 message shown by GitHub Actions is a warning from an action runtime, not the Android build error itself.
