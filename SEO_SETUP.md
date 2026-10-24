# Publish Virtual Camera Android Root v2.0.20 on GitHub

**Repository:** https://github.com/hellowisnu12/Virtual-Camera-Android-Root

**GitHub Pages address after publishing:** https://hellowisnu12.github.io/Virtual-Camera-Android-Root/

**Releases page:** https://github.com/hellowisnu12/Virtual-Camera-Android-Root/releases/tag/v2.0.20

## A. Upload the website and README

1. Create the GitHub repository **hellowisnu12/Virtual-Camera-Android-Root** as **Public** if it does not already exist.
2. Extract this ZIP locally. On the repository page choose **Add file → Upload files**.
3. Upload the **contents of this folder** (not the ZIP or a parent directory). The repository root must contain `README.md`, `index.html`, `SEO_KEYWORDS.md`, and the `assets/` directory.
4. Commit the files. GitHub will render `README.md` automatically on the repository home page.
5. Enable **Settings → Pages → Deploy from a branch → main → / (root) → Save**. Your page is expected at https://hellowisnu12.github.io/Virtual-Camera-Android-Root/ once Pages deploys successfully.

## B. Publish 3 APKs as GitHub Release assets (NOT as source files)

1. Open **https://github.com/hellowisnu12/Virtual-Camera-Android-Root/releases** and choose **Draft a new release**.
2. Create tag **`v2.0.20`** and title **`Virtual Camera Android Root 2.0.20`**.
3. Upload the following three distinct APK binaries to the release's **Assets** section. Use the exact names below. If File Explorer hides `.apk`, check the actual filename, rather than adding a second extension.

```text
VCAR-2.0.20-protected-arm64-v8a.apk
VCAR-2.0.20-protected-x86_64.apk
VCAR-2.0.20-protected-armeabi-v7a.apk
```

4. Add release notes describing version, architecture compatibility, Android/root/LSPosed requirements, and which streaming app workflows have actually been tested. A sample is provided in `RELEASE_NOTES.md`.
5. Click **Publish release**. Only now will these three planned direct-download URLs work:

- **ARM 64-bit:** https://github.com/hellowisnu12/Virtual-Camera-Android-Root/releases/download/v2.0.20/VCAR-2.0.20-protected-arm64-v8a.apk
- **x86 64-bit:** https://github.com/hellowisnu12/Virtual-Camera-Android-Root/releases/download/v2.0.20/VCAR-2.0.20-protected-x86_64.apk
- **ARM 32-bit:** https://github.com/hellowisnu12/Virtual-Camera-Android-Root/releases/download/v2.0.20/VCAR-2.0.20-protected-armeabi-v7a.apk

6. Open each link in a private browser session to confirm it downloads the correct `.apk`, not a GitHub error page.

**Do not upload proprietary Android Studio source, signing keys, `.jks` files, license server code or production secrets.** The three APK binaries are **not included** in this ZIP; only promotional assets and preconfigured links are included.

## C. Google SEO and distribution checks

- `index.html` has a planned GitHub Pages canonical URL and Open Graph preview URL using https://hellowisnu12.github.io/Virtual-Camera-Android-Root/. Those will be valid after GitHub Pages deployment. Update them if using a custom domain.
- Confirm images and assets work on the live page.
- Add the GitHub Pages link in **Repository → About → Website** and add relevant repository topics.
- Submit your published URL to Google Search Console if you own/verify the property.
- Verify Android manifest SDK levels and ABI requirements against each **real** APK before public compatibility claims.
- Replace any speculative copy with confirmed tests. Illustrative promotional graphics are not evidence of universal social media app compatibility.
- SEO can improve discoverability but cannot guarantee first place on Google.

## Why do GitHub download URLs contain `VCAR`?

The APK filenames in your screenshot start with `VCAR-2.0.20-protected-`. GitHub release asset URLs must match the **actual filename**, so they retain this prefix. The public marketing/product name remains **Virtual Camera Android Root**.

## GitHub repo description

`Virtual Camera Android Root — stream gallery videos via a virtual camera on rooted Android devices. Three APK architectures, LSPosed integration, guides and downloads.`

Suggested topics: `virtual-camera-android-root`, `android-root`, `lsposed`, `android-virtual-camera`, `gallery-video`, `live-streaming`, `android-apk`.
