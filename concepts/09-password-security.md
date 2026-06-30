# Password Security & SSPR

**Azure AD Password Protection:**
- Blocks common passwords (Microsoft's banned password list + custom list)
- Applies to both cloud and on-prem AD (via proxy agent)
- Hybrid: installs on DC, intercepts all password changes

**Self-Service Password Reset (SSPR):**
- Users reset their own passwords without calling the helpdesk
- Reduces support tickets by 20-30% in enterprise environments
- Auth methods: authenticator app, email, phone, security questions
- Requires 2 methods for reset (recommended)
- Writeback: syncs password changes back to on-prem AD

**Password hash sync vs PTA vs ADFS:**
- Password Hash Sync: hash synced to Azure AD — simplest, most resilient
- Pass-through Auth: validates against on-prem DC in real-time
- ADFS: full federation — most complex, most control

**Key settings to enable:**
- Entra ID Smart Lockout (lock after N bad attempts)
- Block known-leaked credentials (Entra ID Protection)
- Require password change on risky sign-in

**Exam relevance:** SC-300 Topic 1, Security+ Domain 4
