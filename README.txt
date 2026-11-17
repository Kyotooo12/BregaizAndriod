BREGAIZ ANDROID WRAPPER

This is a basic Android WebView wrapper for the existing online PHP system.
It loads: https://bregaizsystem.fwh.is

BUILD FROM GITHUB (phone-friendly workflow):
1. Create a new GitHub repository named BregaizAndroid.
2. Upload the contents of this ZIP to the repository root (not the ZIP itself).
3. Open the repository's Actions tab.
4. Select "Build Bregaiz Android App" and tap "Run workflow".
5. When complete, open the workflow run and download the artifact named Bregaiz-Android-Build.

The artifact contains a debug APK for installation and a release AAB signed with a temporary debug key for classroom testing. This is not a Play Store production signing setup.

IMPORTANT:
- The app needs internet access.
- It uses the same website and online database as the browser version.
- It does not make the PHP system work offline.
- Before final submission, test login and the required Course and Subject CRUD actions on the phone.
