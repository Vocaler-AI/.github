# Security Policy

This policy applies org-wide to all **Vocaler AI** repositories that do not define their own `SECURITY.md`.

## Reporting a vulnerability
**Please report security issues privately — do not open public issues, PRs, or discussions for vulnerabilities.**

- Email **security@vocaler.ai** (fallback: **hi@vocaler.ai**), or
- Use **GitHub → Security → Report a vulnerability** (private advisory) where enabled.

Include: affected repo/component, a description, reproduction steps or PoC, and impact. We aim to acknowledge within **5 business days** and will keep you updated through resolution.

## Scope & supported versions
The `main` branch of each repository is supported. Production services are operated by Vocaler AI.

## Handling of data & secrets
- Payments are processed by Stripe; we do **not** store card details.
- User-uploaded media and rendered outputs are transient and removed on a short retention window.
- **Never commit secrets.** Use environment variables / a secrets manager; example files must contain placeholders only. If a secret is exposed, rotate it immediately and notify the addresses above.

Thank you for helping keep Vocaler AI and our users safe.
