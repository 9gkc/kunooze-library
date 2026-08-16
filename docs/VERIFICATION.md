# Verify a CyKun Reader Download

Every official release lists the APK file name and its SHA-256 checksum. Download only from the [official CyKun Releases page](https://github.com/9gkc/cykun/releases) when a verified Reader build is listed, then compare the checksum shown on that release page with the file you downloaded.

On a computer with a SHA-256 utility, run:

```text
sha256sum <downloaded-apk-file>
```

The output must exactly match the checksum published beside the same APK asset. If it does not match, delete the download and obtain it again from the official release page.

Android also verifies the app signature during installation and updates.[1]

## Reference

[1] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
