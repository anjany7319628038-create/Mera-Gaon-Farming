# मेरा गाँव – Farming Simulator (v1.0)

A simple 2D Hindi farming game packaged for Android using Capacitor.

## Features
- 6 farm plots
- Wheat, rice and corn seeds
- Water crops, advance days and harvest
- Earn virtual in-game coins

## Build APK with GitHub Actions
1. Create a new GitHub repository.
2. Upload all files in this ZIP to the repository (keep `.github/workflows/build.yml`).
3. Open the repository's **Actions** tab.
4. Select **Build Android APK** and press **Run workflow** (or push to `main`).
5. When the run finishes, open it and download the artifact named `Mera-Gaon-Farming-debug-apk`.
6. Extract the artifact ZIP; it contains `app-debug.apk`.

This project builds a debug APK for testing. A Play Store release requires a signed release build and compliance with Google Play policies. If you are under 18, ask a parent/guardian to manage developer accounts and any monetization setup.

## Local build
Install Node.js, Java 17 and Android SDK, then run:
```bash
npm install
npx cap add android
npx cap sync android
cd android
./gradlew assembleDebug
```

Coins are fictional game points and cannot be withdrawn or exchanged for cash.
