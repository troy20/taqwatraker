# TaqwaTraker

Ready React + Vite + Capacitor project.

## Build on your computer
```bash
npm install
npm run build
npx cap add android
npx cap sync android
npx cap open android
```
Then in Android Studio:
Build > Build Bundle(s) / APK(s) > Build APK(s)

APK path:
android/app/build/outputs/apk/debug/app-debug.apk

## Build APK automatically
Upload this folder to GitHub, then run Actions > Build Android APK. Download the artifact.
