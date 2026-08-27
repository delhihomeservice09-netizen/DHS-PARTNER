# DHS Partner - GitHub APK Build

1. Upload the contents of this folder to the root of your GitHub repository (do not upload the outer ZIP folder as a single file).
2. Commit the files to `main` (or `master`).
3. Open **Actions** -> **Build DHS Partner APK**.
4. If it has not run automatically, press **Run workflow**.
5. Wait for the green check.
6. Open the completed workflow run and download the artifact **DHS-Partner-debug-APK**.
7. The downloaded ZIP contains `app-debug.apk`.

The workflow uses Java 17 and Gradle 8.7 and builds `:app:assembleDebug`.
