# Security Policy

## Supported Versions

Only the following versions of this project are currently receiving security updates. We strongly recommend using the latest stable release.

| Version   | Supported          | Support Type                        | End of Life |
|-----------|--------------------|-------------------------------------|-------------|
| 5.1.x     | :white_check_mark: | Full support (features + security)  | —           |
| 5.0.x     | :white_check_mark: | Security updates only               | TBD         |
| 4.0.x     | :white_check_mark: | Security updates only               | 2026-12-31  |
| < 4.0     | :x:                | Not supported                       | —           |

**Note**: Once a version reaches End of Life, it will no longer receive security patches. Please upgrade as soon as possible.

## Reporting a Vulnerability

**We take all security issues seriously.** If you believe you have found a security vulnerability, please report it responsibly so we can address it before public disclosure.

### Preferred Reporting Methods

1. **GitHub Security Advisories** (Recommended)  
   [Report a vulnerability here](https://github.com/OWNER/REPO/security/advisories/new)

2. **Email**  
   `security@yourproject.org`

3. **PGP Encrypted Email** (Highly Sensitive Reports)  
   [Download our PGP Key](https://yourproject.org/security.asc)  
   **Key ID**: `0x1234ABCD...`  
   **Fingerprint**: `.... .... .... .... .... .... .... .... .... ....`

Please provide the following details in your report:
- Vulnerability description and potential impact
- Affected version(s)
- Steps to reproduce the issue
- Any suggested fixes or workarounds
- Your contact information and preferred name/handle for credit

### Our Response Process

- **Initial Acknowledgment**: Within **48 hours**
- **Triage & Assessment**: Within **5 business days**
- **Status Updates**: At least every **7 days**
- **Patch Release**: Target of **30 days** for high/critical issues (faster for critical)

We follow **Coordinated Vulnerability Disclosure (CVD)**. You will be credited in the advisory and release notes unless you prefer to stay anonymous.

### Scope

**In scope:**
- Vulnerabilities in the core codebase
- Security issues in official dependencies
- Configuration weaknesses in official documentation

**Out of scope:**
- Social engineering or phishing attacks
- Physical access attacks
- Denial of Service against our infrastructure
- Vulnerabilities in unsupported (EOL) versions

## Security Practices

- Automated dependency scanning (Dependabot + Trivy)
- Regular security audits
- Code signing for releases (when applicable)
- Strict code review and CI/CD security checks

## Acknowledgments

We greatly value the security research community. Valid reports are publicly acknowledged in our changelog and on our [Security Hall of Fame](https://github.com/OWNER/REPO/security/acknowledgements) (if available).

Thank you for helping keep this project and its users secure.

---

**Legal Note**: By submitting a report, you agree to follow responsible disclosure practices and not publicly disclose the vulnerability until we have coordinated a fix and release.
