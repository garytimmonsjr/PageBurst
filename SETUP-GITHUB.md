# Putting PageBurst on GitHub (one-time, ~10 minutes)

> Delete this file before uploading. It's just instructions for you.

1. **Create an account** at <https://github.com/signup> (free) if you don't have one.
2. **Create the repo:** click **+ → New repository**
   - Name: `pageburst`
   - Visibility: **Public** (release downloads are only public on public repos)
   - Don't add a README or license (we have our own), then click **Create repository**
3. **Upload these files:** on the new repo page click **uploading an existing file**, then drag in everything from this folder:
   `README.md`, `PRIVACY.md`, `CHANGELOG.md`, `icon.png`, `social-preview.png`, the `screenshots` folder and the `.github` folder.
   (If the `.github` folder doesn't drag in, create the files by hand with **Add file → Create new file** and type the path,
   e.g. `.github/ISSUE_TEMPLATE/bug_report.yml`.) Then click **Commit changes**.
4. **Social preview:** repo **Settings → General → Social preview → Edit → Upload an image** and pick `social-preview.png`.
   This is the picture Reddit and Discord show when someone shares your link.
5. **About box:** on the repo's main page click the ⚙️ next to **About**:
   - Description: `Offline manga & comic reader for Android: CBZ, CBR, PDF, EPUB`
   - Topics: `android`, `manga`, `comics`, `manga-reader`, `comic-reader`, `cbz`, `epub`
6. **First release:** follow *Each release* in `RELEASING.md` in the app project (build the signed APK →
   **Releases → Draft a new release** → tag `v0.1.0` → attach `PageBurst-v0.1.0.apk` → tick **pre-release** → **Publish**).
7. **Privacy policy link** (useful for Google Play later): `https://github.com/YOUR-USERNAME/pageburst/blob/main/PRIVACY.md`

Your download link to share everywhere: `https://github.com/YOUR-USERNAME/pageburst/releases/latest`
