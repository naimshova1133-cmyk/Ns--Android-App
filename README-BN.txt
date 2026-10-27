# NS11 Neon Arcade — Android APK project

This project wraps the bundled `app/src/main/assets/index.html` arcade site in an Android WebView.

## Build an APK on GitHub (phone-friendly)
1. Create a new GitHub repository, for example `ns11-android-app`.
2. Upload the contents of this folder (including `.github/workflows/build-apk.yml`) to the repository's `main` branch.
3. Open the repository's **Actions** tab.
4. Select **Build NS11 Android APK** and press **Run workflow** (or wait for the push-triggered build).
5. When the workflow finishes successfully, open the run and download the **NS11-Neon-Arcade-APK** artifact.
6. Extract the downloaded ZIP to get `app-debug.apk`, then install it on your Android phone. Android may ask you to allow installs from your browser/files app.

This is a debug APK for personal testing, not a Play Store release. It contains no real-money betting or cashout. Demo scores/profile are local to the app.
