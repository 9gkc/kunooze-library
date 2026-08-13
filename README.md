# Kunooze Library Reader

> **Student-facing Android reader for the Kunooze academic library.**

**Kunooze Library Reader** is an Arabic, right-to-left Android application for browsing academic cybersecurity materials published by the library owner. Students can explore academic years and subjects, read structured text lessons inside the app, and open approved Google Drive PDF resources.

> **المكتبة الرقمية الأكاديمية لطلاب الأمن السيبراني.** التطبيق مخصص للطلاب فقط: تصفح المواد المنشورة، اقرأ الدروس النصية داخل التطبيق، وافتح ملفات PDF المعتمدة.

## Download

| Item | Link | Details |
|---|---|---|
| Latest reader APK | [Download v1.2.0](https://github.com/9gkc/kunooze-library-reader/releases/download/v1.2.0/kunooze-library-reader-v1.2.0.apk) | Android reader release APK |
| Release page | [View release notes](https://github.com/9gkc/kunooze-library-reader/releases/tag/v1.2.0) | Version details and checksum |
| Installation guide | [Open the student guide](docs/INSTALLATION.md) | Arabic installation steps |

The APK is a signed production release, not a debug or trial build. Its SHA-256 checksum is:

```text
9331a872addf0dc6f2ed7f46b54caad4006461b59e4074a6d1b992fd6200679a
```

## What students can do

| Feature | Student experience |
|---|---|
| Arabic RTL interface | Read the entire application in an Arabic right-to-left layout. |
| Academic navigation | Move from the academic year to the subject, then to published learning materials. |
| In-app text lessons | Read structured text materials without leaving the application. |
| Approved PDF resources | Open owner-approved, viewer-only Google Drive PDF links. |
| No student account | Browse published material without creating or signing in to an account. |
| Searchable catalogue | Search by academic year, subject, or material title. |
| Student guide | Follow an in-app, three-step guide for using the library. |

## Screenshots

The following screenshots are captured from the reader application's actual Flutter interface at a mobile-sized viewport. They use local example academic records solely to show the interface; the material available to students is controlled by the library owner in Firebase.

| Home | Academic catalogue | Student guide |
|---|---|---|
| ![Kunooze Reader home screen](images/reader-home.png) | ![Kunooze Reader catalogue](images/reader-catalog.png) | ![Kunooze Reader student guide](images/reader-guide.png) |

## Installation note

Version 1.2.0 uses a replacement owner-controlled signing certificate because the historical v1.1 signing key was not recoverable. Android requires an existing application and its update to be signed with the same certificate. If v1.1 is already installed, uninstall it first, then install v1.2.0. Published library content remains in Firebase and is not removed by this device-side step. [1]

The application needs internet access to retrieve published content and to open PDF resources. Android may also ask the student to allow installation from the browser or file manager used to download the APK. [2]

## Scope of this public repository

This is a **binary distribution repository**, not a source-code repository. It deliberately contains only the student reader release, screenshots, verification data, and student documentation.

| Included | Not included |
|---|---|
| Reader APK as a GitHub Release asset | Application source code |
| Public screenshots and installation guide | Owner publisher APK |
| Version and checksum information | Signing keys, Firebase configuration, and owner credentials |

The private development repository remains private to protect the owner publishing workflow and operational configuration. Students should download **only the Reader APK** from this page.

## References

[1] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)

[2] [Android Help — Download and install Android apps](https://support.google.com/android/answer/9450271)
