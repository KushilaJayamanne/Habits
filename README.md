# Habit Tracker: turn it into an Android app (APK)

## 1. Put the app online with GitHub Pages (free)
1. Sign in at github.com and tap **+ → New repository**. Name it `habits`, set it to **Public**, and tap **Create repository**.
2. Tap **uploading an existing file** (or **Add file → Upload files**) and add all 6 files from this zip:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`.
   Upload them loose, not inside a folder. Then tap **Commit changes**.
3. Go to **Settings → Pages**. Under "Branch", choose **main** and **/ (root)**, then tap **Save**.
4. Wait 1–2 minutes. Your app's address will be `https://YOUR-USERNAME.github.io/habits/`. Open it to check that it works.

## 2. Make the APK with PWABuilder (free)
1. Go to **pwabuilder.com**, paste your address from step 1, and tap **Start**.
2. Tap **Package for stores → Android → Generate package** (the default options are fine).
3. Download the zip it gives you. Inside it is an **.apk** file.

## 3. Install it on your phone
1. Open the .apk on your phone (from Downloads or Files).
2. If Android asks, allow **Install unknown apps** for that app (Chrome or Files).
3. Tap **Install**. "Habits" now appears in your app drawer.

## Good to know
- Your check-ins are saved on your phone. Uninstalling the app or clearing its data erases them.
- To update the app later, upload a changed `index.html` to GitHub. The installed app picks up the change the next time it's opened with internet.
