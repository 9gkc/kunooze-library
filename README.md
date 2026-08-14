# Kunooze Library

> **The official Android Reader for the Kunooze academic digital library.**

**Kunooze Library** is an Arabic, right-to-left application for students who access university cybersecurity material. The Reader presents one calm, coherent route through the academic structure: **Stage → Semester → Subject → Numbered lecture**. It is designed for studying, not for managing content: students can browse without creating an account, read published lessons, open owner-approved PDF resources, follow lectures in sequence, and view active announcements or timetable notices.

## Official download

| Item | Link | Purpose |
|---|---|---|
| Latest Reader APK | [Download Kunooze Library v1.0.1](https://github.com/9gkc/kunooze-library/releases/download/v1.0.1/kunooze-library-reader-v1.0.1.apk) | Install the signed student Reader. |
| Release page | [Open the v1.0.1 corrective release](https://github.com/9gkc/kunooze-library/releases/tag/v1.0.1) | Review the release asset and notes. |
| Installation guide | [Read the guide](docs/INSTALLATION.md) | Install or update safely on Android. |
| Verification record | [Verify the download](docs/VERIFICATION.md) | Compare version, signature, size, and checksum. |

The official package is **`kunooze-library-reader-v1.0.1.apk`**. It is a signed production APK, not a debug or trial build.

```text
SHA-256: 6ddf204d36eb7a2c9b73f2c226665df0ddb6bb1b0dab1ab42aa9eca8e3d138db
```

## A corrected academic Reader experience

| Capability | Student benefit |
|---|---|
| Refined shield identity | The familiar Kunooze shield returns in an improved, clearer form for Android and the Arabic interface. |
| University-first structure | Start directly with one of the four stages; every stage contains exactly its first and second semester. |
| Clear academic path | Move through **Stage → First/Second Semester → Subject → Numbered Lecture** with no extra academic level. |
| Deterministic lecture flow | Lectures follow their publisher-assigned number; older materials with a numbered title have a stable fallback order. |
| Text and PDF learning | Read written lessons in the app or open owner-approved PDF resources. |
| Search and notices | Search published catalogue items and view active announcements or timetable entries. |
| No student account | Browse published content without registration or sign-in. |

## Interface preview

The following screenshot is an authentic golden render of the corrected Reader home screen at a mobile viewport. It intentionally uses the application’s pending-data state, so the zero counts are **not** a representation of the live library catalogue.

![Kunooze Library corrected Reader home](images/reader-home-v1.0.1.png)

## Installation and updates

The corrected Reader is version **`1.0.1`** with Android version code **`8`**. It uses the same production package identity and signing certificate as preceding official production builds, so Android can update an official Reader installation directly.

If Android reports that an older installation cannot be updated, it was signed with an earlier identity. In that specific one-time case, uninstall the old app and install the current official APK. Library materials remain remotely maintained by the owner and are not embedded in the app package.

## Public distribution scope

This is a **public binary-distribution repository** for students. It contains only the Reader APK, verification material, English documentation, and current Reader interface imagery.

| Available here | Deliberately excluded |
|---|---|
| Signed Reader APK | Application source code |
| Reader documentation and checksum | Publisher APK and owner workflow |
| Reader screenshot | Signing keys and Firebase configuration |
| Android installation guidance | Credentials, unpublished materials, and student records |

Students should download only the Reader APK from the official release page and may share the unmodified official link with classmates.

## References

[1] [Android Help — Download and install Android apps](https://support.google.com/android/answer/9450271)
