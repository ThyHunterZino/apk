# Monthly Challenge – Android APK

## Get the APK (about 10 minutes, on a computer)
1. Create a free account at github.com and make a **new repository** (private is fine).
2. Upload everything from this folder to it, keeping the folders as they are.
   Make sure `.github/workflows/build-apk.yml` is included. If your upload skips it:
   "Add file → Create new file", type `.github/workflows/build-apk.yml` as the name,
   and paste the contents of that file.
3. Open the **Actions** tab → **Build Android APK**. It starts by itself after the upload;
   otherwise press **Run workflow**.
4. When it turns green (5–10 min), open the run and download **MonthlyChallenge-apk**
   under Artifacts. Unzip it to get `app-debug.apk`.
5. Send the APK to your phone, open it, and allow "Install unknown apps" when asked.

## Notes
- Data is stored inside the app on the phone. Use Backup / Import in the app to keep a copy.
- Export PDF is hidden in the Android app (printing isn't supported there).
- To change the app, edit `www/index.html` and push again.
