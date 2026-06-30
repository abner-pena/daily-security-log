# Zero Trust Architecture

"Never trust, always verify." Eliminate implicit trust based on network location.

**Three pillars:**
1. **Verify explicitly** — always authenticate and authorize using all available signals
2. **Least privilege access** — limit access with JIT, JEA, risk-based policies
3. **Assume breach** — minimize blast radius, segment access, encrypt everything

**Identity is the new perimeter:**
- Traditional model: trusted internal network = trusted user
- Zero Trust: every access request verified regardless of where it comes from

**Implementation in Azure:**
- Entra ID Conditional Access for policy enforcement
- Intune for device compliance signals
- Microsoft Defender for Endpoint for device health
- Privileged Identity Management (PIM) for JIT admin access

**Exam relevance:** Security+ Domain 3 & 4, SC-300 across all topics
