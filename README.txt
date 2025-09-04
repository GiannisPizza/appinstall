# Gianni’s Pizza — GitHub Files (Root + Android Studio Project)

**Repo root** (for GitHub Pages at https://giannispizza.github.io/appinstall/):
- index.html — landing page with 3 buttons (Android source, Android APK, iPhone Web Clip profile)
- index_debug.html — quick link tester
- logo.png — placeholder logo (replace with your brand)
- GiannisPizza_WebClip.mobileconfig — iOS Web Clip profile (installs home-screen icon)
- manifest.plist — kept for future Ad Hoc iOS (requires IPA + Apple Developer)
- GiannisAndroid_StudioProject.zip — zipped Android Studio project (for direct download)

**Android Studio project folder** is also included at /GiannisAndroid_StudioProject (for a separate repo or local editing).

Next steps:
1) Upload ALL files in this bundle to your repo root (public).
2) Enable GitHub Pages (Settings → Pages → Deploy from a branch → main / root).
3) Build/sign the Android APK using the Studio project; upload APK as a GitHub Release asset, then keep the Android button URL as-is (or update filename/version if different).
4) For iPhone native install later, export an Ad Hoc IPA, upload as a Release asset, and update manifest.plist accordingly.
