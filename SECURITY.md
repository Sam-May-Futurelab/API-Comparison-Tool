# Security Policy

## Supported Versions

We take security seriously and will address security vulnerabilities in the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | ✅ Yes            |
| < 1.0   | ❌ No             |

## Reporting a Vulnerability

If you discover a security vulnerability in the API Documentation Comparison Tool, please report it responsibly:

### 🔒 Private Disclosure

**Please do NOT open a public issue for security vulnerabilities.**

Instead, please report security issues by:

1. **Email**: Send details to [your-email@example.com] (replace with actual email)
2. **GitHub Security**: Use GitHub's [private vulnerability reporting](https://github.com/Sam-May-Futurelab/API-Comparison-Tool/security/advisories/new)

### 📝 What to Include

Please include the following information in your report:

- **Description**: A clear description of the vulnerability
- **Steps to Reproduce**: Detailed steps to reproduce the issue
- **Impact**: What could an attacker potentially do?
- **Browser/Environment**: Which browsers or environments are affected
- **Proof of Concept**: Any code or screenshots demonstrating the issue (if safe to share)

### ⏱️ Response Timeline

We will acknowledge your report within **48 hours** and provide a detailed response within **7 days** indicating:

- Confirmation of the issue
- Our assessment of the severity
- Expected timeline for a fix
- Any additional information needed

### 🛡️ Security Considerations

This project is a client-side application with the following security considerations:

#### Current Security Measures
- **No Server Communication**: All processing happens client-side
- **No Data Persistence**: No data is stored on external servers
- **Input Sanitization**: HTML content is properly escaped
- **XSS Prevention**: User input is sanitized before display

#### Potential Security Areas
- **Content Security Policy (CSP)**: Could be enhanced
- **Input Validation**: User-provided documentation content
- **DOM Manipulation**: Dynamic HTML generation
- **Third-party Dependencies**: Highlight.js and TailwindCSS CDN

#### Out of Scope
- **Browser Vulnerabilities**: Issues in the browser itself
- **CDN Security**: Issues with third-party CDN providers
- **Local File System**: Issues related to local file access (by design)
- **Social Engineering**: Non-technical attacks

### 🏆 Security Hall of Fame

We appreciate security researchers who help keep our project safe. Confirmed security reporters will be:

- Listed in our Security Hall of Fame (with permission)
- Credited in release notes
- Given recognition in our README

### 📚 Additional Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Mozilla Web Security Guidelines](https://infosec.mozilla.org/guidelines/web_security)
- [Google's Web Security Guide](https://developers.google.com/web/fundamentals/security)

---

Thank you for helping keep the API Documentation Comparison Tool and our users safe! 🛡️
