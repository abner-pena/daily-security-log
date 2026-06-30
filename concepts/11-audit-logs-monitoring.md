# Audit Logs & Sign-In Monitoring in Entra ID

**Sign-in Logs:**
- Every authentication attempt: success and failure
- Key fields: UPN, IP, location, app, CA policy applied, MFA detail, risk level
- Retention: 30 days (7 days for non-interactive, 30 for interactive) — export to Log Analytics for longer

**Audit Logs:**
- All changes made to directory objects (users, groups, apps, policies)
- Who changed what, when, and from where
- Key operations to watch: role assignments, app consent grants, CA policy changes

**What to monitor:**
- Failed sign-ins (brute force detection)
- Sign-ins from new/unusual locations
- New Global Admin role assignments
- App consent grants (OAuth consent phishing)
- Legacy auth usage (should be zero after blocking)

**Export destinations:**
- Log Analytics Workspace → Sentinel for alerting
- Storage Account → long-term archival
- Event Hub → SIEM integration (Splunk, QRadar)

**Exam relevance:** SC-300 Topic 4, Security+ Domain 4
