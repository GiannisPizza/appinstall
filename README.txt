# Gianni’s Pizza — Starter Kit (Root Files)

Put these files in the **root** of a public GitHub repo and enable **GitHub Pages** (Settings → Pages → Deploy from a branch → main / root).

Files:
- index.html — landing page (Android APK + iOS Ad Hoc)
- manifest.plist — OTA manifest (root IPA + root logo)
- index_debug.html — test page to verify links
- logo.png — placeholder (replace with your brand)
- GiannisPizza.ipa — **you add this** (Ad Hoc export from Xcode)

Replace `YOUR-USERNAME` in all files with your GitHub username.
If IPA > 100MB, host the IPA as a GitHub Release asset and put that asset URL in manifest.plist <url>.
