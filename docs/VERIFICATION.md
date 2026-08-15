# Verify CyKun Reader v1.0.0 Production Refresh

Use this record to confirm that the file you downloaded is the official public CyKun Reader release.

| Property | Expected value |
|---|---|
| Product | CyKun Reader |
| User-visible version | `1.0.0` |
| Android version code | `11` |
| APK filename | `CyKun-Reader-v1.0.0-production.apk` |
| Package identifier | `com.alkarara.kunooze.library_app` |
| File size | `63,108,398 bytes` |
| SHA-256 | `a99d0165c3d234b428abd2dee47cf6686355ef41f24622464f561d9ad39fbfc6` |
| Signing certificate SHA-1 | `93:32:D7:B4:F4:0C:DE:60:32:2B:DB:4F:C3:E0:C4:4A:69:A6:1A:C4` |
| Verified signing schemes | APK Signature Scheme v2 and v3 |

## Compare the SHA-256 value

On a computer, calculate the downloaded file’s SHA-256 hash and compare it character-for-character with the value above.

```bash
sha256sum CyKun-Reader-v1.0.0-production.apk
```

The result must be an exact match. A different hash means the file is not this published artifact and should not be installed.

## Verify the Android signature

Android verifies the package signature during installation. The release was also checked with Android’s APK verification tooling for v2 and v3 signing. APK signing identifies update-compatible releases and protects the integrity of the installed package.[1]

## Official locations

| Resource | Link |
|---|---|
| Release page | [CyKun v1.0.0 Production Refresh](https://github.com/9gkc/cykun/releases/tag/cykun-1.0.0-production-20260815) |
| Current checksum file | [checksums.txt](../checksums.txt) |
| Installation guide | [INSTALLATION.md](INSTALLATION.md) |

## References

[1] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
