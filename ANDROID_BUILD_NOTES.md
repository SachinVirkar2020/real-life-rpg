# Android APK build notes

This is an offline-capable PWA source package, not a compiled APK. A signed APK requires Android Studio/Android SDK and a signing key.

To build a native Android wrapper, use Capacitor with this web app as its web assets, run `npx cap add android` and `npx cap sync android`, then open the Android project in Android Studio and build a signed APK.

Progress is stored locally in browser/WebView storage. No account or cloud connection is required.
