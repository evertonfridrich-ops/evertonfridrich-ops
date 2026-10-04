# Security Policy

## Reporting a Vulnerability

We take the security of our public tools, profiles, and associated software seriously. If you identify a potential security vulnerability, please notify us responsibly.

### Coordinated Disclosure

* **Contact Email:** `evertonfridrich@gmail.com`
* **Response Time:** We aim to acknowledge receipt within 48 business hours.
* **Scope:** This policy applies to public repositories and workflows hosted under the `evertonfridrich-ops` organization/user namespace.

Please include the following in your report:
1. Detailed description of the suspected vulnerability.
2. Steps or proof-of-concept to reproduce the behavior safely.
3. Potential impact assessment.
4. Any suggested mitigation or patch.

**Please do NOT open public GitHub Issues or Discussions for undisclosed security vulnerabilities.**

## Security Standards & Supply Chain

* All GitHub Actions workflows operate under the principle of least privilege, with explicit read-only token scopes where possible.
* Software artifacts use deterministic builds, lockfiles, and dependency vulnerability monitoring.
