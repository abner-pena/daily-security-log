# SSO: SAML vs OAuth vs OIDC

**SAML 2.0 (Security Assertion Markup Language)**
- XML-based, older protocol
- Used for enterprise SSO (on-prem to cloud federation)
- Flow: SP → IdP → assertion → SP grants access
- Best for: legacy enterprise apps, Salesforce, on-prem apps via ADFS

**OAuth 2.0**
- Authorization framework (not authentication)
- Grants apps limited access to resources on behalf of a user
- Tokens: access token, refresh token
- Best for: API authorization, mobile apps

**OpenID Connect (OIDC)**
- Authentication layer built on top of OAuth 2.0
- Adds ID token (JWT) to confirm who the user is
- Used by: Azure AD, Google, modern SaaS apps
- Best for: modern web/mobile apps

**In Azure Entra ID:**
- OIDC/OAuth: Microsoft identity platform (MSAL)
- SAML: enterprise gallery apps, custom SAML apps
- WS-Federation: legacy Microsoft apps

**Exam relevance:** SC-300 Topic 1 & 3, Security+ Domain 4
