# RBAC vs ABAC

**RBAC (Role-Based Access Control)**
Access is granted based on job role. Simple to manage at scale.
- Azure built-in roles: Owner, Contributor, Reader
- Custom roles: define exact permissions
- Best for: stable organizations with clear job functions

**ABAC (Attribute-Based Access Control)**
Access is granted based on attributes (department, location, clearance level).
- Azure ABAC: conditions on role assignments (e.g., only access blobs with tag = HR)
- More flexible but more complex to manage
- Best for: data-level access control, dynamic environments

**When to use which:**
- Use RBAC as your baseline — assign roles at appropriate scope
- Layer ABAC conditions for fine-grained data access
- Combine with Conditional Access for context-aware decisions

**Exam relevance:** Security+ Domain 4, SC-300 Topic 3
