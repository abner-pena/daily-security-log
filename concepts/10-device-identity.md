# Device Identity in Entra ID

How devices establish trust with your tenant — required for device-based Conditional Access.

**Three join types:**

| Type | Use case | Management |
|---|---|---|
| Entra ID Registered | BYOD — personal devices | Limited MDM |
| Entra ID Joined | Cloud-only corporate Windows | Intune / full MDM |
| Hybrid Entra ID Joined | Existing on-prem AD domain joined | Group Policy + Intune |

**Device compliance (Intune):**
- Define what "compliant" means: disk encryption, antivirus, OS version, PIN
- Conditional Access checks compliance state before granting access
- Non-compliant devices → block or require remediation

**Windows Hello for Business:**
- Replaces password with PIN or biometric on the device
- Backed by TPM chip — credential never leaves the device
- Phishing-resistant (no password to steal)
- Requires Entra ID Join or Hybrid Join

**Exam relevance:** SC-300 Topic 2, Security+ Domain 3
