# Hybrid Identity — Azure AD Connect

Sync on-premises Active Directory to Entra ID (Azure AD).

**Azure AD Connect sync:**
- Syncs users, groups, contacts from on-prem AD to Entra ID
- Runs on a Windows Server in your on-prem environment
- Sync interval: every 30 minutes (default)
- Delta sync: only changes since last sync

**Authentication options:**
| Method | Description | Best for |
|---|---|---|
| Password Hash Sync | Hashed passwords synced to cloud | Most orgs — simple, resilient |
| Pass-through Auth | Validates against on-prem DC | Must not store passwords in cloud |
| Federation (ADFS) | External IdP handles auth | Complex compliance requirements |

**Key features:**
- Password writeback: cloud password resets sync back to on-prem
- Device writeback: Hybrid Entra ID Joined devices registered in on-prem AD
- Group writeback: cloud groups written back to on-prem

**Health monitoring:**
- Azure AD Connect Health — monitors sync, alerts on failures
- Check sync errors in Entra admin center → Connect Health

**Exam relevance:** SC-300 Topic 1
