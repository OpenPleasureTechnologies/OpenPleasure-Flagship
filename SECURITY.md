# Security Policy – Open Pleasure Labs

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.x (production) | ✅ |
| 0.x (beta) | ⚠️ Security issues accepted, no SLAs |
| main branch (development) | ✅ Security issues accepted |

## Reporting a Vulnerability

**Do NOT open a public issue for security vulnerabilities.**

Instead, email: `security@openpleasure.org` (set this up)

We will:
- Acknowledge within 48 hours
- Provide regular updates (every 5 days)
- Fix within 14 days (if critical)
- Disclose publicly after fix + 30 days (to allow patching)

## Known Vulnerability Scope

| Component | Risk | Mitigation |
|-----------|------|------------|
| BLE pairing | ECDH implementation bug | Use audited crypto library (mbedTLS) |
| Firmware updates | Signature bypass | Ed25519, verify on every boot |
| USB-C power | Overvoltage | BQ25601 protection (hardware) |
| On-device data | Encryption key extraction | Secure element for key storage (v2) |

## Encryption Details

- **BLE:** ECDH (P-256) + AES-CCM
- **Storage:** AES-256-GCM, key derived from PBKDF2 (100k iterations)
- **Firmware:** Ed25519 signatures, public key burned into OTP

## Responsible Disclosure

We follow **90-day disclosure policy** (Google standard):

1. Reporter finds bug, emails security@
2. We confirm within 48h
3. We fix within 90 days
4. Public disclosure after fix or at 90 days (whichever is earlier)

## Bug Bounty

We currently offer **no monetary bug bounty** (open source project).  
We offer: credit in release notes, sticker pack, and our eternal gratitude.

---

**Security is a feature, not an afterthought.**
