# Reader Release Verification

- Application: CyKun Reader
- Version: 1.0.1+13
- Artifact: `downloads/CyKun-Reader-1.0.1+13.apk`
- SHA-256: `e05c63d473fc656cc3c5a42dfaf58892a574276e6cc0395b9bc24051953eb944`
- Signature: Android APK Signature Scheme v2 and v3 verified
- Scope: Reader APK and student-facing documentation only

Verify locally with:

```bash
sha256sum downloads/CyKun-Reader-1.0.1+13.apk
apksigner verify --verbose downloads/CyKun-Reader-1.0.1+13.apk
```
