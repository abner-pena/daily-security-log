# Multi-Factor Authentication Methods

MFA requires two or more of: something you know, have, or are.

**Methods ranked by security (strongest first):**
1. FIDO2 / Hardware security keys (YubiKey) — phishing-resistant
2. Microsoft Authenticator push + number match
3. TOTP (time-based one-time password) apps
4. SMS/voice — weakest, vulnerable to SIM swapping

**Azure-specific:**
- Conditional Access can enforce MFA per app, location, or risk level
- Authentication Strength policy lets you require specific MFA methods
- MFA registration campaign: push users to register without blocking access

**Exam relevance:** Security+ Domain 4, SC-300 Topic 2
