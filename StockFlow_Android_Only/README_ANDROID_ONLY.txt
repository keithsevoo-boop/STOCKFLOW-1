StockFlow Android-only project

This package contains only the Android scanner app and the GitHub Actions workflow to build its APK. It does not contain the Windows EXE or Windows desktop application files.

GitHub upload:
1. Create a new repository.
2. Upload the contents of this folder, including the .github folder and android folder.
3. Commit the files.
4. Open Actions and run "Build StockFlow Android APK" (or let it run after a push).
5. When successful, open the workflow run and download the StockFlow-Scanner-APK artifact.

The generated app-debug.apk is a test/debug APK, not a Play Store release.
