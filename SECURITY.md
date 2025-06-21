# Security Policy

## 🛡️ Supported Versions

We actively support the following versions of the Frostpunk 2 Offline Setup Assistant with security updates:

| Version | Supported          |
| ------- | ------------------ |
| 2.1.x   | ✅ Yes            |
| 2.0.x   | ✅ Yes            |
| 1.9.x   | ⚠️ Limited        |
| < 1.9   | ❌ No             |

## 🔒 Security Commitment

The Frostpunk 2 Offline Setup Assistant is designed with security as a top priority:

- **🚫 No Network Requirements**: Completely offline operation prevents network-based attacks
- **🔐 Local File Access Only**: No external connections or data transmission
- **✅ Open Source**: All code is transparent and auditable
- **🛡️ Minimal Permissions**: Requests only necessary system permissions

## 📝 Reporting a Vulnerability

If you discover a security vulnerability, please help us maintain the security of our users by following responsible disclosure:

### 🚨 Critical Security Issues
For critical vulnerabilities that could compromise user systems:
- **Email**: security@frostpunk2setup.com
- **PGP Key**: Available at [our website](https://frostpunk2setup.com/pgp-key.txt)
- **Response Time**: Within 24 hours

### ⚠️ Non-Critical Security Issues
For minor security concerns:
- **GitHub Issues**: Use the "Security" label
- **Response Time**: Within 72 hours

### 📧 What to Include
When reporting a vulnerability, please include:

1. **Description**: Clear explanation of the vulnerability
2. **Impact**: Potential consequences and affected components
3. **Reproduction**: Step-by-step instructions to reproduce
4. **Environment**: Operating system, version, and configuration
5. **Evidence**: Screenshots, logs, or proof of concept (if safe)

### Example Report Template
```
Subject: [SECURITY] Brief description of vulnerability

Description:
[Detailed explanation of the security issue]

Impact:
[What could an attacker accomplish]

Steps to Reproduce:
1. [Step one]
2. [Step two]
3. [Result]

Environment:
- OS: Windows 11 Pro
- Assistant Version: v2.1.0
- Affected Component: [installer/UI/config]

Additional Information:
[Any other relevant details]
```

## 🔄 Security Response Process

### 1. Acknowledgment
- We acknowledge receipt within 24 hours
- Assign a tracking ID for the report
- Initial assessment of severity level

### 2. Investigation
- Security team investigates the issue
- Reproduce the vulnerability in controlled environment
- Assess impact and develop mitigation strategies

### 3. Resolution
- Develop and test security patch
- Coordinate release timeline
- Prepare security advisory

### 4. Disclosure
- Notify reporter of resolution
- Public disclosure after patch deployment
- Credit reporter (if desired) in security advisory

## 🏆 Vulnerability Rewards

While we don't offer monetary bounties, we recognize security researchers through:

- **🎖️ Security Hall of Fame**: Recognition on our website
- **📜 Certificate**: Digital certificate of appreciation
- **👕 Swag**: Project merchandise for significant findings
- **🤝 Direct Communication**: Access to our security team

## 🛡️ Security Best Practices for Users

### Safe Installation
- **✅ Download from official sources only**
- **✅ Verify file hashes before installation**
- **✅ Run antivirus scan on downloaded files**
- **✅ Install in standard user account (not admin)**

### System Security
- **🔒 Keep your OS updated**
- **🛡️ Use reputable antivirus software**
- **🔐 Enable Windows Defender or equivalent**
- **📥 Only download from trusted repositories**

### File Permissions
- **📁 Review folder permissions after installation**
- **🔒 Don't run setup assistant as administrator unless required**
- **📋 Check what files the assistant accesses**

## ⚠️ Known Security Considerations

### File System Access
The setup assistant requires access to:
- **Game installation directory**: For configuration files
- **User documents folder**: For save game management
- **Temporary folder**: For extraction and processing
- **Registry access**: For game settings (Windows only)

### Network Isolation
- **✅ No outbound connections**: Assistant works completely offline
- **✅ No telemetry**: No usage data collected or transmitted
- **✅ No auto-updates**: Manual updates only for security control

### Code Signing
- **Windows**: Executables are code-signed with our certificate
- **macOS**: Notarized for Gatekeeper compatibility
- **Linux**: GPG signatures provided for package verification

## 🔍 Security Auditing

### External Audits
- Annual security review by independent researchers
- Automated vulnerability scanning in CI/CD pipeline
- Community-driven security testing

### Internal Security Measures
- **Code Review**: All changes reviewed by security-aware developers
- **Static Analysis**: Automated code scanning for vulnerabilities
- **Dependency Scanning**: Regular checks for vulnerable dependencies
- **Sandboxed Testing**: All builds tested in isolated environments

## 📜 Security-Related Dependencies

We maintain awareness of security issues in our dependencies:

### JavaScript/Node.js
- Regular updates to latest stable versions
- Automated dependency vulnerability scanning
- Manual review of security advisories

### Python
- Pin dependency versions for consistency
- Monitor security advisories for all packages
- Use virtual environments for isolation

### System Libraries
- Document all system dependencies
- Test compatibility with security updates
- Provide alternative implementations where possible

## 🚨 Incident Response

### Security Incident Classification

**🔴 Critical (P0)**
- Remote code execution vulnerabilities
- Privilege escalation issues
- Data corruption risks

**🟡 High (P1)**
- Local privilege escalation
- Information disclosure
- Denial of service attacks

**🟢 Medium (P2)**
- Configuration vulnerabilities
- Input validation issues
- Minor information leaks

**🔵 Low (P3)**
- Cosmetic security issues
- Theoretical vulnerabilities
- Documentation improvements

### Response Timeline
- **P0**: Fix within 24 hours
- **P1**: Fix within 72 hours
- **P2**: Fix within 1 week
- **P3**: Fix in next planned release

## 📞 Contact Information

### Security Team
- **Primary Contact**: security@frostpunk2setup.com
- **Lead Security Officer**: Alex Chen (alex.chen@frostpunk2setup.com)
- **Emergency Contact**: +1-555-SECURITY (for critical issues)

### PGP Public Key
```
-----BEGIN PGP PUBLIC KEY BLOCK-----
[PGP key would be here in real implementation]
-----END PGP PUBLIC KEY BLOCK-----
```

### Alternative Contact Methods
- **Signal**: +1-555-SECURE-01
- **Keybase**: @frostpunk2security
- **Discord**: Security Team (verified server members only)

## 📋 Security Checklist for Contributors

Before submitting code:
- [ ] No hardcoded credentials or secrets
- [ ] Input validation for all user data
- [ ] Proper error handling without information leakage
- [ ] Secure file handling practices
- [ ] No unnecessary permissions requests
- [ ] Dependencies reviewed for known vulnerabilities
- [ ] Code follows secure coding guidelines

## 🔄 Updates to This Policy

This security policy is reviewed and updated:
- **Quarterly**: Regular review schedule
- **As Needed**: After security incidents
- **Community Input**: Based on user feedback

**Last Updated**: December 2024
**Next Review**: March 2025

---

We take security seriously and appreciate your help in keeping the Frostpunk 2 Offline Setup Assistant safe for all users. Together, we can ensure that everyone can enjoy the game securely and privately. 🛡️❄️ 