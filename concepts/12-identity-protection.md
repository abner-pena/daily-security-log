# Microsoft Entra ID Protection

Risk-based identity security — detects anomalies and can automatically respond.

**Risk types:**

*User risk* — likelihood that the user's identity is compromised
- Leaked credentials (Microsoft monitors dark web / breach databases)
- Unusual patterns of activity

*Sign-in risk* — likelihood that the specific sign-in is not the legitimate user
- Anomalous token
- Impossible travel
- Malicious IP
- Unfamiliar sign-in properties

**Risk levels:** Low, Medium, High

**Responses (via Conditional Access or risk policies):**
- Medium sign-in risk → require MFA
- High sign-in risk → block access
- High user risk → require password change
- Block if sign-in risk ≥ High

**ID Protection reports:**
- Risky users: accounts flagged as compromised
- Risky sign-ins: specific sign-ins that were suspicious
- Risk detections: individual risk events that triggered the flag

**Exam relevance:** SC-300 Topic 2, Security+ Domain 4
