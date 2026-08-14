# Installation Guide

This guide is for students who want to install the **Kunooze Library** reader. Download and install the Reader APK only; the owner publishing application is not intended for student devices or public distribution.

## Install Kunooze Library

| Step | Action |
|---|---|
| 1 | Download [Kunooze Library v1.0.0](https://github.com/9gkc/kunooze-library/releases/download/v1.0.0/kunooze-library-reader-v1.0.0.apk) from the official release. |
| 2 | Uninstall any previously installed Kunooze Library APK once. This transition build establishes a new permanent production signing identity. |
| 3 | Install `v1.0.0` (version code `6`). Future official updates will install directly over this build. |
| 4 | Open the downloaded APK and choose **Install**. If Android requests permission, allow the trusted browser or file manager to install apps from this source. [1] |
| 5 | Open **Kunooze Library**. Students do not need to create an account or sign in. |

## Use the Reader

Start from the Home tab and select **Explore materials**, or open the Library tab directly. Choose a stage, then a semester, then a subject, and finally a published material. Text lessons are available in the app. Approved PDF resources open through their published Google Drive links.

The Home tab can display owner-published announcements or temporary timetable entries while they are active. If a material is not visible, it has not been published yet or the device is offline. Students do not need to configure Firebase or Google Drive.

## Verify the Download

Students who want to verify the file can compare the downloaded APK checksum with the following SHA-256 value:

```text
8126da885f5ca759f9fcf4615f7036b5c6e6c1ff422cf2d11058d157ddff432f
```

The APK is signed with Android APK Signature Scheme v2. The complete package metadata and certificate fingerprint are listed in [VERIFICATION.md](VERIFICATION.md). Android explains the purpose of APK signing in its official documentation. [2]

## References

[1] [Android Help — Download and install Android apps](https://support.google.com/android/answer/9450271)

[2] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
