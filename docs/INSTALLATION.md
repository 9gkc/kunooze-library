# Installation Guide

This guide is for students who want to install the **CyKun** Reader. CyKun means **Cyber Kunooze / سايبر الكنوز**. Download and install the Reader APK only; the owner publishing application is not intended for student devices or public distribution.

## Install or update CyKun

| Step | Action |
|---|---|
| 1 | Download [CyKun v1.0.0](https://github.com/9gkc/cykun/releases/download/v1.0.0/cykun-reader-v1.0.0.apk) from the official release. |
| 2 | If an official Reader is already installed, open the new APK and choose **Update** when Android offers it. Version code `10` is newer than the prior official builds. |
| 3 | If Android refuses the update because the installed app has a different signature, uninstall that older copy once, then install the official APK. |
| 4 | If Android requests permission, allow only the trusted browser or file manager that downloaded the APK to install apps from that source. [1] |
| 5 | Open **CyKun**. Students do not need to create an account or sign in. |

## Use the Reader

Start on **Home** and select an academic stage. Each stage has only the **First Semester** and **Second Semester**. Choose a semester, then a subject, then its numbered published lecture. Text lessons are available in the application. Owner-approved PDF resources open through their published Google Drive links.

The Home tab can display owner-published announcements or temporary timetable entries while they are active. The **Community** tab contains the official [CyS4Ever Telegram channel](https://t.me/cys4ever) and the [developer’s LinkedIn profile](https://www.linkedin.com/in/9gkc/). If a material is not visible, it has not been published yet or the device is offline. Students do not need to configure Firebase or Google Drive.

## Verify the download

Compare the downloaded APK checksum with:

```text
df24f9196e2b7c31f42b798ad44a8abf649ad3906a0b379035d600d29fcc0b87
```

The APK is signed with Android APK Signature Schemes v2 and v3. Its complete package metadata and certificate fingerprint are listed in [VERIFICATION.md](VERIFICATION.md). Android explains the purpose of APK signing in its official documentation. [2]

## References

[1] [Android Help — Download and install Android apps](https://support.google.com/android/answer/9450271)

[2] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
