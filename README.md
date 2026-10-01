# BigPrompter - Android APK + iOS project

## Android APK (free, ~5 minutes, no software to install)
1. Create a free account at github.com and make a new repository (e.g. "bigprompter").
2. Upload ALL files from this folder (keep the .github folder and its structure).
3. Open the repo > Actions tab > "Build Android APK" runs automatically (or press Run workflow).
4. When it turns green, open the run > Artifacts > download "BigPrompter-android-apk".
5. Unzip, copy app-debug.apk to your phone/tablet, open it, allow "install unknown apps". Same APK works on phone and tablet.

## iPhone / iPad
- Fastest (no Apple account): host www/index.html (GitHub Pages / Netlify), open the link in Safari > Share > Add to Home Screen.
- Real iOS app: needs an Apple Developer account ($99/yr). Run the "Build iOS (unsigned)" workflow, then sign the archive in Xcode
  on a Mac, or tell your developer to open ios/ after `npm install && npx cap add ios && npx cap sync ios`.

## Remote
Switch the remote to KEY mode (side slider) and pair it in Bluetooth settings. Open Settings > Remote buttons to see what each
button sends ("Last remote input") and reassign any button. GAME mode also works (gamepad buttons + stick).
