# MSSOUGRA Landing Page

Static download page for the MSSOUGRA sports prediction APK.

## Usage

Open `index.html` in a browser, or serve with:

```bash
python3 -m http.server 8080
```

## Adding the APK

Build the APK from the `app` branch, then copy it here:

```bash
cp ../web-app-to-react-native/android/app/build/outputs/apk/release/app-universal-release.apk ./mssougra-v1.0.0.apk
```

Update the version number in `index.html` (the size badge, the quick-stats, and the filename above).
