# Tarang releases

Public home for [Tarang](https://github.com/animeshahilya/Radio)'s update manifest and release
APKs. The Radio source repo is private; this repo exists purely so the app's in-app updater
(`AppUpdateManager`) can fetch [latest.json](./latest.json) and download a new APK without
authentication.

- `latest.json` - `versionCode`/`versionName`/`apkUrl`/`notes` for the newest published build.
- Each GitHub Release here (tagged `v<versionName>`, e.g. `v1.6`) carries that version's
  `app-release.apk`.

Nothing here is meant to be browsed directly - see the main
[Radio repo](https://github.com/animeshahilya/Radio) for the actual app, source, and changelog.
