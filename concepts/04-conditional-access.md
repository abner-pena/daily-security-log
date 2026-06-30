# Conditional Access Policies

The "if-then" engine of Entra ID: IF (user/app/condition) THEN (allow/block/require).

**Signal inputs (conditions):**
- User or group membership
- IP location (named locations, trusted ranges)
- Device platform and compliance state
- Application being accessed
- Sign-in risk level (Entra ID Protection)
- User risk level

**Grant controls:**
- Require MFA
- Require compliant device
- Require hybrid Azure AD join
- Require approved client app
- Block access

**Common policies to implement first:**
1. Require MFA for all users
2. Block legacy authentication
3. Require compliant device for Office 365
4. Block high-risk sign-ins

**Exam relevance:** SC-300 Topic 2, Security+ Domain 4
