# Security Policy

## Supported Versions

We release patches for security vulnerabilities in the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 0.1.x   | :white_check_mark: |

## Reporting a Vulnerability

We take the security of Mentcare Frontend System seriously. If you believe you have found a security vulnerability, please report it to us as described below.

### How to Report

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via:

1. **GitHub Security Advisories**: Use the [GitHub Security Advisory](https://github.com/Mojakhomo/Mentcare-frontend-system/security/advisories) feature
2. **Email**: Contact the repository maintainers directly

### What to Include

Please include the following information in your report:

- Type of vulnerability
- Full paths of source file(s) related to the vulnerability
- Location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the vulnerability
- Proof-of-concept or exploit code (if possible)
- Impact of the vulnerability, including how an attacker might exploit it

### Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 7 days
- **Resolution**: Depends on complexity, but we aim for 30-90 days

## Security Best Practices

### For Users

- Keep your browser up to date
- Use HTTPS when serving the application
- Do not expose sensitive patient data in production without proper backend authentication
- Implement proper access controls

### For Contributors

- Never commit sensitive information (passwords, API keys, etc.)
- Follow secure coding practices
- Validate all user inputs
- Use HTTPS for all external resources
- Keep dependencies updated

## Disclosure Policy

When we receive a security bug report, we will:

1. Confirm the problem and determine affected versions
2. Audit code to find similar problems
3. Prepare fixes for all supported versions
4. Release patches as soon as possible

Thank you for helping keep Mentcare Frontend System and its users safe!
