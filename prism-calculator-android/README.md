# Prism Calculator Android

This is an Android WebView wrapper for the colourful calculator.

## Build APK

1. Install Android Studio or Android command-line tools with JDK 17.
2. Open this folder in Android Studio.
3. Let Gradle sync.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).

Command-line build after installing the Android SDK and Gradle:

```powershell
gradle :app:assembleDebug
```

The APK will be created at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

This workspace could not compile the APK because Java, Gradle, and the Android SDK are not installed locally.
