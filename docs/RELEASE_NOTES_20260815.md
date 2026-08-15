# CyKun Reader v1.0.0 — Production Hotfix

## Public Reader update

This is the signed Android Reader update that includes the owner-approved CyKun Beta improvements and corrects production connectivity. The public version name stays at `1.0.0`; its Android version code is raised to `12` so it can update the affected official Reader installation in place. The existing academic library remains in Firebase and was not deleted or recreated.

| Release item | Details |
|---|---|
| APK | `CyKun-Reader-v1.0.0-production.apk` |
| User-visible version | `1.0.0` |
| Android version code | `12` |
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
| SHA-256 | `e61b3353703b154adcacd658d3fc38f175bf2bf5b21b85788260e74f1ecd16a8` |
| Signing schemes checked | v2 and v3 |

Android verifies the package signature during installation. The release also passed Android APK signature verification before publication.[1]

## Reference

[1] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
