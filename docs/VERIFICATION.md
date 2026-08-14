# Verify CyKun Reader v1.0.0

Use this record to confirm that the file you downloaded is the official public CyKun Reader release.

| Property | Expected value |
|---|---|
| Product | CyKun Reader |
| User-visible version | `1.0.0` |
| Android version code | `10` |
| APK filename | `cykun-reader-v1.0.0.apk` |
| Package identifier | `com.alkarara.kunooze.library_app` |
| File size | `59,685,809 bytes` |
| SHA-256 | `df24f9196e2b7c31f42b798ad44a8abf649ad3906a0b379035d600d29fcc0b87` |
| Signing certificate SHA-1 | `93:32:D7:B4:F4:0C:DE:60:32:2B:DB:4F:C3:E0:C4:4A:69:A6:1A:C4` |
| Verified signing schemes | APK Signature Scheme v2 and v3 |

## Compare the SHA-256 value

On a computer, calculate the downloaded file’s SHA-256 hash and compare it character-for-character with the value above.

```bash
sha256sum cykun-reader-v1.0.0.apk
```

The result must be an exact match. A different hash means the file is not this published artifact and should not be installed.

## Verify the Android signature

Android verifies the package signature during installation. The release was also checked with Android’s APK verification tooling for v2 and v3 signing. APK signing identifies update-compatible releases and protects the integrity of the installed package.[1]

## Official locations

| Resource | Link |
|---|---|
| Release page | [CyKun v1.0.0](https://github.com/9gkc/cykun/releases/tag/v1.0.0) |
| Current checksum file | [checksums.txt](../checksums.txt) |
| Installation guide | [INSTALLATION.md](INSTALLATION.md) |

## References

[1] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
