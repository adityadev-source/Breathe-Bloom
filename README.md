# Breathe & Bloom — iPhone Home-Screen App

This folder is a **Progressive Web App (PWA)** edition of Breathe & Bloom. It runs in Safari and can be added to an iPhone Home Screen so it opens in an app-like window. It is not an App Store IPA and it does not require installing a configuration profile, enabling Developer Mode, jailbreaking, or connecting the phone to a computer.

## Easiest safe path

1. **Preview first.** Publish the files to an HTTPS website (the free GitHub Pages method below is one option). Open the link in Safari on the iPhone and try the app as a normal website first. No app installation is needed to test it.
2. Only after it looks right, open the same link in Safari, tap **Share**, choose **Add to Home Screen**, enable **Open as Web App** if shown, then tap **Add**.
3. To remove the Home Screen icon later, press and hold it and choose **Remove Bookmark** or **Remove App** (wording can vary by iOS version). Removing the icon does not damage iOS.

## Publish with GitHub Pages (free)

Publishing makes the website and its source files publicly reachable. Do not add passwords, personal details, or private photos to this folder/repository.

1. On a computer, sign in to GitHub or create an account with help from a parent/guardian if needed.
2. Create a **public** repository, for example `breathe-and-bloom`.
3. Upload the contents of this folder into the repository's top level. The top level must contain `index.html`, `manifest.webmanifest`, `sw.js`, and the `assets` folder. Upload the files themselves, not an extra enclosing folder.
4. Open the repository **Settings → Pages**. Under build and deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for GitHub Pages to finish publishing. The website address will look like `https://YOUR-USERNAME.github.io/breathe-and-bloom/`.
6. Open that address in Safari on the iPhone and test it before adding it to the Home Screen.

## What to know

- Practice history and preferences use browser-local storage on that device. They are not sent to an app account or synced automatically to Android.
- Offline caching is included, but the very first successful visit needs an internet connection. Test offline behaviour only after the site has loaded once.
- iPhone browser vibration is not supported consistently, so start/end cues use gentle audio tones where the browser allows audio. Keep the phone's volume at a comfortable level.
- This is not a native iOS app and cannot be submitted to the App Store as-is. A native build needs a Mac with Xcode and additional setup.
- The yoga guidance is general wellness information. Move within a comfortable range and stop if anything hurts or feels wrong.
