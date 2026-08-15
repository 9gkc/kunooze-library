# CyKun Reader v1.0.0 — Production Refresh

## Public Reader update

This is the signed Android Reader update that promotes the owner-approved CyKun Beta improvements to production. The public version name stays at `1.0.0`; its Android version code is raised to `11` so it can update the preceding official public Reader installation in place.

| Release item | Details |
|---|---|
| APK | `CyKun-Reader-v1.0.0-production.apk` |
| User-visible version | `1.0.0` |
| Android version code | `11` |
| Download | [Official release asset](https://github.com/9gkc/cykun/releases/download/cykun-1.0.0-production-20260815/CyKun-Reader-v1.0.0-production.apk) |
| Verification | [Verification record](VERIFICATION.md) |

## Included improvements

| Area | What students receive |
|---|---|
| Faster entry | The first interface appears immediately while Firebase initialises in the background. |
| Calm presentation | Persisted light and dark themes, plus automatic Arabic RTL and English LTR direction. |
| Focused notifications | Only newly published content is shown; opening a notification goes directly to the intended item and marks it read locally. |
| Cleaner interface | Removed nonessential guiding copy from the Reader. |
| Original brand mark | A brief opening treatment and Android adaptive icon that preserve the original CyKun shield without a black outer field. |

## Verification summary

| Property | Value |
|---|---|
| Package identifier | `com.alkarara.kunooze.library_app` |
| File size | `63,108,398 bytes` |
| SHA-256 | `a99d0165c3d234b428abd2dee47cf6686355ef41f24622464f561d9ad39fbfc6` |
| Signing schemes checked | v2 and v3 |

Android verifies the package signature during installation. The release also passed Android APK signature verification before publication.[1]

## Reference

[1] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
