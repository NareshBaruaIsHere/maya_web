# Maya Website

Landing page for the Maya personal safety and SOS app.

## What's Included

- Hero section with app branding and APK download button
- App feature, screenshots, download, feedback, and privacy sections
- Favicon support using `assets/images/favicon.ico`
- APK download wiring for `assets/downloads/maya.apk`
- Version label shown under the hero download button

## Project Structure

- `index.html` - main landing page
- `privacy.html` - privacy policy page
- `style.css` - site styling
- `script.js` - version text, icons, scroll effects, and APK link handling
- `assets/images/` - favicon, logo, screenshots, and social images
- `assets/downloads/` - APK file for download

## Asset Locations

- Favicon: `assets/images/favicon.ico`
- App logo: `assets/images/logo.png`
- Hero screenshot: `assets/images/screenshot-hero.png`
- Gallery screenshots: `assets/images/screenshot-1.png` to `screenshot-4.png`
- APK: `assets/downloads/maya.apk`

## Run Locally

Open `index.html` directly in a browser, or serve the folder with any local web server if you want the APK download check to behave like a real hosted site.

## Update the App Version

If you want to change the visible version number:

1. Update `APP_VERSION` in `script.js`.
2. The hero version label will update automatically.
3. Keep the APK filename/path in `assets/downloads/` aligned with the version you publish.

## Push Changes to GitHub

After making edits:

```bash
git status
git add -A
git commit -m "Describe your change"
git push origin main
```

If the remote is already configured, that is all you need. If not, add it once:

```bash
git remote add origin https://github.com/NareshBaruaIsHere/maya_website.git
```

## Notes

- The site title no longer shows the version number.
- The version is displayed under the hero APK button instead.
- The favicon is set to `assets/images/favicon.ico`.