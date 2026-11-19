# sca-vuln-go-gin

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** Go modules

## Expected findings (non-exhaustive)
- dgrijalva/jwt-go 3.2.0: CVE-2020-26160
- gin 1.6.0: CVE-2020-28483
- gorilla/websocket 1.4.0: CVE-2020-27813
- x/crypto (2020-02): CVE-2020-29652, CVE-2021-43565
- x/net (2020-08): CVE-2021-33194, CVE-2022-27664
- x/text 0.3.2: CVE-2020-14040, CVE-2022-32149
- yaml.v2 2.2.2: CVE-2019-11254
