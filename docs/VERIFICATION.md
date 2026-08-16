# APK verification

Use this record to confirm that the downloaded file is the official public CyKun Reader release.

| Property | Expected value |
|---|---|
| Product | CyKun Reader |
| User-visible version | `1.0.0` |
| Build variant | `production release` |
| APK filename | `CyKun-Reader-v1.0.0-production.apk` |
| Package identifier | `com.alkarara.kunooze.library_app` |
| SHA-256 | `be75ef98f5f1b12361cb2c36bebb2e44de809b3276b8763952480ad193f12cd2` |
| Verified signing schemes | APK Signature Scheme v2 and v3 |

## Compare the SHA-256 value

On a computer, calculate the downloaded file’s SHA-256 hash and compare it character-for-character with the value above.

```bash
sha256sum CyKun-Reader-v1.0.0-production.apk
```

The result must be an exact match. A different hash means the file is not this published artifact and should not be installed.

## Official locations

| Resource | Link |
|---|---|
| Release page | [CyKun Reader v1.0.0 production release](https://github.com/9gkc/cykun/releases/tag/cykun-1.0.0-production-20260816) |
| Current checksum file | [checksums.txt](../checksums.txt) |
| Installation guide | [INSTALLATION.md](INSTALLATION.md) |

The public repository contains the signed Reader distribution only. Signing keys, Firebase configuration, credentials, Publisher files, and source code are intentionally excluded.

## References

[1] [Android Open Source Project — APK signing](https://source.android.com/docs/security/features/apksigning)
