# Security Policy

## Supported Versions

We provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 0.25.x  | :white_check_mark: |
| 0.24.x  | :white_check_mark: |
| < 0.24  | :x:                |

## Reporting a Vulnerability

We take the security of QQQ seriously. If you believe you have found a security vulnerability, please report it to us responsibly.

### How to Report

**Please DO NOT report security vulnerabilities through public GitHub issues.**

Instead, please send an email to **security@qrun.io** with:

1. **Description** of the vulnerability
2. **Steps to reproduce** the issue
3. **Affected versions** of the software
4. **Potential impact** of the vulnerability
5. **Any suggested fixes** (optional)

### What to Expect

- **Acknowledgment**: We will acknowledge receipt of your report within 48 hours
- **Assessment**: We will investigate and validate the issue within 7 days
- **Updates**: We will keep you informed of our progress
- **Resolution**: We aim to resolve critical issues within 30 days
- **Credit**: We will credit you in the security advisory (unless you prefer to remain anonymous)

### Disclosure Policy

- We follow [coordinated disclosure](https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure)
- We will work with you to understand and resolve the issue
- We ask that you give us reasonable time to address the issue before public disclosure
- We will publish a security advisory once the issue is resolved

## Security Best Practices

When using QQQ in production:

1. **Keep dependencies updated** - Run `mvn versions:display-dependency-updates` regularly
2. **Use environment variables** for secrets - Never commit credentials
3. **Enable authentication** on all endpoints
4. **Review entity permissions** - Use role-based access control
5. **Monitor logs** for suspicious activity
6. **Use HTTPS** for all external communications

## Security-Related Configuration

See the [QQQ Security Documentation](https://github.com/QRun-IO/qqq/wiki/Security) for:

- Authentication setup
- Authorization configuration
- Audit logging
- Data encryption

## Past Security Advisories

Security advisories are published at:
https://github.com/QRun-IO/qqq/security/advisories

---

Thank you for helping keep QQQ and our users safe!
