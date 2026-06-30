# Privileged Identity Management (PIM)

Just-in-time privileged access in Azure — reduces standing admin access.

**Problem it solves:**
Permanent admin roles are a risk. If an admin account is compromised, the attacker has persistent admin access. PIM makes elevated access time-limited and requires explicit activation.

**How it works:**
1. Users are made *eligible* for a role (not permanently assigned)
2. When needed, user *activates* the role for 1-8 hours
3. Activation can require: MFA, justification, manager approval
4. All activations are logged and audited

**Key features:**
- Activation requires justification (audit trail)
- Notifications to security team on activation
- Access reviews for eligible and active assignments
- Just-Enough-Access (JEA) principles

**Azure roles to protect with PIM:**
Global Administrator, Privileged Role Administrator, Security Administrator, User Administrator

**Exam relevance:** SC-300 Topic 4
