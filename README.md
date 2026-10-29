# Vista Native Android TV Launcher

Vista is a native Java Android launcher (not a WebView). It detects launchable installed apps, has Home/Apps/Settings screens, theme choices, recently opened apps, and lets you choose your own image as wallpaper.

## Build on GitHub using a phone
1. Extract this ZIP on your phone.
2. In a browser, create a new GitHub repository named `VistaNative` and set it to Public or Private.
3. Upload the extracted project files and folders to the repository root. Make sure `.github/workflows/build.yml` is included.
4. Open the repository's **Actions** tab and open **Build Vista APK**. If prompted, enable Actions, then press **Run workflow**.
5. When the run finishes green, open that run, scroll to **Artifacts**, and download `Vista-debug-APK`.
6. Extract the downloaded artifact ZIP to get `app-debug.apk`. Transfer the APK to your TV and install it. You may need to allow installation from unknown sources.

## Notes
- Minimum Android version is Android 5.1 (API 22).
- After installing, open Vista and use Settings > Choose background wallpaper.
- To make it the default Home launcher, press the TV remote's Home button and choose Vista if Android TV offers a launcher chooser. Some TV firmware may force its stock home screen.
- This is an initial starter build; device-specific TV firmware can affect launcher selection and wallpaper image providers.
