# Build Daily Reminder APK with GitHub Actions

1. Upload the contents of this folder to the root of an empty GitHub repository.
2. Confirm `.github/workflows/main.yml` is present.
3. Open the repository Actions tab.
4. Select **Build Daily Reminder APK** and choose **Run workflow**.
5. When successful, download the `Daily-Reminder-V2.2-APK` artifact and extract `app-release.apk`.

The workflow generates Android project scaffolding and applies Android core library desugaring before compiling.
A successful workflow run is still required to verify the APK.
