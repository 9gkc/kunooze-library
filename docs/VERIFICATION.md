# Reader Release Verification

- Application: CyKun Reader
- Version: 1.0.1+13
- Artifact: `downloads/CyKun-Reader-1.0.1+13.apk`
- SHA-256: `$(cut -d' ' -f1 checksums.txt)`
- Signature: Android APK Signature Scheme v2 and v3 verified
- Scope: Reader APK and student-facing documentation only

Verify locally with:

```bash
sha256sum downloads/CyKun-Reader-1.0.1+13.apk
apksigner verify --verbose downloads/CyKun-Reader-1.0.1+13.apk
```
