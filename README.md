# CyKun

<p align="center">
  <img src="images/cykun-shield.png" width="108" alt="CyKun shield logo" />
</p>

<p align="center"><strong>Cyber Kunooze — an Arabic academic library for university cybersecurity students.</strong></p>

<p align="center">
  <a href="https://github.com/9gkc/cykun/releases/tag/cykun-1.0.0-production-20260816"><img src="https://img.shields.io/badge/release-v1.0.0-56D6F0?style=for-the-badge" alt="Current release v1.0.0" /></a>
  <img src="https://img.shields.io/badge/platform-Android-1A213B?style=for-the-badge" alt="Android" />
  <img src="https://img.shields.io/badge/interface-Arabic%20RTL-8B7BFF?style=for-the-badge" alt="Arabic right-to-left interface" />
  <a href="https://t.me/cys4ever"><img src="https://img.shields.io/badge/community-CyS4Ever-1A213B?style=for-the-badge" alt="CyS4Ever community" /></a>
</p>

**CyKun Reader** is the official public student application for a university cybersecurity library. It provides a focused route from academic stage to semester, subject, and published lecture without student accounts or unnecessary management features.

> **Built for reading.** Students browse published Arabic lessons and approved PDF resources. Content is managed separately by the owner and remains remote, so an app update does not erase the academic library.

## Download the official Reader

| Resource | Purpose | Link |
|---|---|---|
| Reader APK | Signed production APK for Android students | [Download CyKun Reader v1.0.0](https://github.com/9gkc/cykun/releases/download/cykun-1.0.0-production-20260816/CyKun-Reader-v1.0.0-production.apk) |
| Release page | Release notes, asset, and checksum | [Open the official release](https://github.com/9gkc/cykun/releases/tag/cykun-1.0.0-production-20260816) |
| Installation guide | Safe installation and update steps | [Read the guide](docs/INSTALLATION.md) |
| Verification record | Package identity and SHA-256 | [Verify the APK](docs/VERIFICATION.md) |

**Current asset:** `CyKun-Reader-v1.0.0-production.apk`  
**SHA-256:** `be75ef98f5f1b12361cb2c36bebb2e44de809b3276b8763952480ad193f12cd2`

## Academic route

CyKun follows the university structure without inventing an additional course layer:

| Step | Student action | Result |
|---:|---|---|
| 1 | Select an academic stage | Start from the correct year. |
| 2 | Select the first or second semester | See the subjects for that semester. |
| 3 | Open a subject | Review its published learning materials. |
| 4 | Select a lecture or resource | Read an in-app lesson or open an approved PDF. |

## Reader screenshots

The gallery contains Reader-only Arabic RTL screens. This repository and its documentation are maintained in English; the application interface is designed for Arabic-speaking students.

| Home overview | Academic path | Community and trust |
|---|---|---|
| ![CyKun Reader home screen](images/reader-overview.png) | ![CyKun academic path](images/academic-path.png) | ![CyKun community and trust screen](images/community-and-trust.png) |
| Focused entry point and published study path. | Clear stage, semester, subject, and lecture sequence. | Official community links and safety guidance. |

## Student features

| Feature | Student benefit |
|---|---|
| Stage → semester → subject → lecture | Matches the university structure and keeps navigation predictable. |
| Ordered learning materials | Publisher-defined ordering keeps related lectures together. |
| Text lessons and PDF resources | Read lessons in the app or open approved documents safely. |
| Announcements and publication updates | See relevant academic notices and newly published material in the in-app updates centre. |
| No student account | Browse published content without registration or sign-in. |
| Arabic RTL interface | Designed for comfortable Arabic reading and navigation. |

## Official community

| Presence | Official link |
|---|---|
| CyS4Ever community | [t.me/cys4ever](https://t.me/cys4ever) |
| Ali Alkarar, developer | [LinkedIn profile](https://www.linkedin.com/in/9gkc/) |

CyKun will never ask for a password, verification code, or sensitive account information through Telegram or LinkedIn. Use only the official links above or the links shown inside the Reader.

## Versioning and data safety

The public launch remains displayed as **v1.0.0**. The internal Android version code is incremented for safe installation over the previous official build. Published academic content is managed remotely and is not deleted by installing this APK.

If Android does not offer an in-place update, verify that the installed package came from an official CyKun release before removing it. Always verify the SHA-256 value before installation.

## Repository scope

This is a **public Reader distribution repository**. It intentionally excludes all source code, Publisher tools, owner workflows, signing keys, Firebase configuration, credentials, and unpublished academic content.

For the complete source and owner-only Publisher package, use the private owner repository. Do not request or redistribute its protected files.

## References

[1] [Android Help — Download and install Android apps](https://support.google.com/android/answer/9450271)  
[2] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
