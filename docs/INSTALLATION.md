# Installation Guide

This guide is for students who want to install the **Kunooze Library** Reader. Download and install the Reader APK only; the owner publishing application is not intended for student devices or public distribution.

## Install or update Kunooze Library

| Step | Action |
|---|---|
| 1 | Download [Kunooze Library v1.0.0](https://github.com/9gkc/kunooze-library/releases/download/v1.0.0/kunooze-library-reader-v1.0.0.apk) from the official release. |
| 2 | If the previously installed official Reader is version code `6`, open the new APK and choose **Update** when Android offers it. |
| 3 | If Android refuses the update because the installed app has a different signature, uninstall that older copy once, then install the official APK. |
| 4 | If Android requests permission, allow only the trusted browser or file manager that downloaded the APK to install apps from that source. [1] |
| 5 | Open **Kunooze Library**. Students do not need to create an account or sign in. |

## Use the Reader

Start on **Home** and select **Start from the library**, or open the **Library** tab directly. Choose a stage, semester, subject, and then a numbered published lecture. Text lessons are available in the application. Owner-approved PDF resources open through their published Google Drive links.

The Home tab can display owner-published announcements or temporary timetable entries while they are active. If a material is not visible, it has not been published yet or the device is offline. Students do not need to configure Firebase or Google Drive.

## Verify the download

Compare the downloaded APK checksum with:

```text
f6bb3d24e7247f22672b462e8904fd2d55772e9c8c79852e480649afafeb1a12
```

The APK is signed with Android APK Signature Scheme v2. Its complete package metadata and certificate fingerprint are listed in [VERIFICATION.md](VERIFICATION.md). Android explains the purpose of APK signing in its official documentation. [2]

## References

[1] [Android Help — Download and install Android apps](https://support.google.com/android/answer/9450271)

[2] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
