# Daily Security Log

Daily study log — IAM concepts, Security+ prep, and SC-300 material. One entry every day, automated via GitHub Actions.

**Cert journey:** Security+ (Aug 2026) → SC-300: Microsoft Identity & Access Administrator (Sep 2026)

---

Last updated: 2026-06-29
Total entries: 1

---

## What's in here

Each day a GitHub Action runs at 9am ET and commits a new log entry to `logs/YYYY-MM-DD.md`. The entry rotates through 14 core IAM and security concepts covering:

- Identity lifecycle (provisioning, deprovisioning, access reviews)
- Azure Entra ID (Conditional Access, PIM, Identity Protection, SSO)
- Security controls (MFA, Zero Trust, RBAC, device identity)
- Hybrid identity (Azure AD Connect, password hash sync)

## Concept rotation

14 concepts rotate daily — one full cycle every two weeks:

| # | Concept |
|---|---|
| 01 | Identity Lifecycle Management |
| 02 | MFA Methods & Strength |
| 03 | RBAC vs ABAC |
| 04 | Conditional Access Policies |
| 05 | Zero Trust Architecture |
| 06 | Privileged Identity Management (PIM) |
| 07 | SSO: SAML vs OAuth vs OIDC |
| 08 | Access Reviews |
| 09 | Password Security & SSPR |
| 10 | Device Identity in Entra ID |
| 11 | Audit Logs & Sign-In Monitoring |
| 12 | Microsoft Entra ID Protection |
| 13 | Entitlement Management |
| 14 | Hybrid Identity & Azure AD Connect |

## Setup

```bash
git clone https://github.com/abner-pena/daily-security-log
cd daily-security-log
# Push to GitHub — Actions runs automatically at 9am ET daily
```

No configuration needed. The workflow uses `GITHUB_TOKEN` (provided automatically by GitHub Actions).
