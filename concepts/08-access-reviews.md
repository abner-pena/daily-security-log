# Access Reviews (Entra ID Governance)

Periodic, structured review of who has access to what — and whether they still need it.

**Why it matters:**
Access creep: users accumulate permissions over time. Access reviews enforce hygiene.

**Review types:**
- Group membership reviews
- Application assignment reviews
- Azure role reviews (via PIM)
- Privileged role reviews

**Review settings:**
- Frequency: weekly/monthly/quarterly/annual
- Reviewers: manager, resource owner, or self-review
- Auto-apply results: automatically remove access if reviewer denies/doesn't respond
- Fallback: if reviewer doesn't respond → remove access (recommended)

**Process:**
1. Create review → assign reviewers → reviewers get email/My Access portal link
2. Reviewer approves or denies each assignment
3. Results applied (manually or automatically)
4. Audit log captures all decisions

**Exam relevance:** SC-300 Topic 4 (Identity Governance)
