---
name: security-practices
description: Master security and compliance. Covers OWASP, secure coding, cryptography, authentication, authorization, cloud security, and compliance frameworks.
sasmp_version: "1.3.0"
bonded_agent: 01-web-frontend
bond_type: PRIMARY_BOND
---

# Security & Compliance Skill

Master security practices and compliance frameworks.

## OWASP Top 10 (2024)

### 1. Broken Access Control
- Unauthorized access to resources
- Missing access control checks
- Vertical privilege escalation

### 2. Cryptographic Failures
- Weak encryption algorithms
- Sensitive data exposure
- Poor key management

### 3. Injection
- SQL injection
- Command injection
- NoSQL injection
- Code injection

### 4. Insecure Design
- Missing security controls
- Threat modeling gaps
- Insufficient security by design

### 5. Security Misconfiguration
- Unpatched systems
- Unnecessary features enabled
- Default credentials
- Debug mode in production

### 6. Vulnerable & Outdated Components
- Known vulnerabilities in dependencies
- No security update process
- Unsupported software

### 7. Authentication Failures
- Weak password policies
- Session fixation
- Credential stuffing
- Brute force attacks

### 8. Data Integrity Failures
- Insecure CI/CD pipelines
- Tampered data
- Serialization vulnerabilities

### 9. Logging & Monitoring Failures
- Insufficient logging
- No alerting mechanisms
- Failure to detect breaches

### 10. SSRF (Server-Side Request Forgery)
- Accessing internal resources
- Port scanning
- Data exfiltration

## Secure Coding Practices

### Input Validation
- Whitelist acceptable inputs
- Reject invalid data early
- Use parameterized queries (prevent SQL injection)
- Sanitize user input

### Output Encoding
- HTML encoding
- URL encoding
- JavaScript encoding
- CSS encoding
- Prevent XSS attacks

### Common Vulnerabilities

**SQL Injection Prevention:**
- Use parameterized queries
- Prepared statements
- ORMs (SQLAlchemy, Sequelize)

**Cross-Site Scripting (XSS):**
- Input validation
- Output encoding
- Content Security Policy (CSP)

**Cross-Site Request Forgery (CSRF):**
- CSRF tokens
- SameSite cookies
- Origin/Referer validation

**Broken Authentication:**
- Strong password requirements
- MFA/2FA implementation
- Secure session management
- Password hashing (bcrypt, scrypt)

## Cryptography

### Symmetric Encryption
- **AES-256** (standard choice)
- Block cipher modes: GCM, CBC
- Key management

### Asymmetric Encryption
- **RSA** - Traditional
- **ECC** - Elliptic Curve (modern, efficient)
- Key pair management

### Hashing
- **SHA-256, SHA-3** for general use
- **bcrypt, scrypt** for passwords (never plain hash)
- HMAC for authentication

### TLS/SSL
- TLS 1.3 (current standard)
- Certificate pinning
- Perfect forward secrecy
- HSTS headers

## Authentication & Authorization

### Authentication Methods
- **Password-Based** (combined with MFA)
- **Multi-Factor Authentication (MFA)**
  - TOTP (Time-based One-Time Password)
  - SMS (less secure)
  - Hardware keys (most secure)
- **OAuth 2.0** (delegated auth)
- **OpenID Connect** (authentication layer over OAuth)
- **SAML** (enterprise SSO)

### Authorization Models
- **RBAC** - Role-Based Access Control
- **ABAC** - Attribute-Based Access Control
- **PBAC** - Policy-Based Access Control
- **Principle of Least Privilege**

### Session Management
- Secure session tokens
- HttpOnly cookies (prevent XSS)
- Secure flag (HTTPS only)
- SameSite attribute (prevent CSRF)
- Session timeout
- Token expiration

## Cloud Security

### Shared Responsibility Model
- **Cloud Provider**: Infrastructure, platform, managed services
- **Customer**: Data, applications, access management, configurations

### IAM Best Practices
- Least privilege access
- Multi-factor authentication
- Regular key rotation
- Service accounts for applications
- Audit logging

### Data Protection
- Encryption at rest (EBS, S3)
- Encryption in transit (TLS)
- Key management (AWS KMS, GCP KMS)
- DLP (Data Loss Prevention)

### Network Security
- VPCs for isolation
- Security groups and NACLs
- Private subnets
- VPN/bastion hosts
- WAF (Web Application Firewall)

## Compliance Frameworks

### GDPR (EU Data Protection)
- User consent
- Right to be forgotten
- Data portability
- Privacy by design

### HIPAA (Healthcare)
- Protected health information (PHI)
- Access controls
- Audit logs
- Encryption requirements

### PCI-DSS (Payment Cards)
- Secure network architecture
- Cardholder data protection
- Access control
- Regular security testing

### SOC 2 (Service Organizations)
- Security, availability, integrity
- Confidentiality, privacy
- Trust controls

### ISO 27001
- Information security management
- Risk assessment
- Security controls
- Compliance verification

## Security Tools

### Vulnerability Scanning
- **Snyk** - Dependency scanning
- **OWASP ZAP** - Web app scanning
- **Burp Suite** - Web security testing
- **SonarQube** - Code quality and security

### Monitoring
- **SIEM**: Splunk, ELK, DataDog
- **Intrusion Detection**: Snort, Suricata
- **CloudTrail** (AWS), **Cloud Logging** (GCP)

### Secrets Management
- **HashiCorp Vault**
- **AWS Secrets Manager**
- **Google Secret Manager**
- **Azure Key Vault**

## Security Checklist

- [ ] Implement HTTPS/TLS everywhere
- [ ] Use strong password hashing (bcrypt, argon2)
- [ ] Implement MFA
- [ ] Regular security updates
- [ ] Input validation and sanitization
- [ ] Parameterized queries (prevent SQL injection)
- [ ] CORS properly configured
- [ ] Security headers (CSP, HSTS, X-Frame-Options)
- [ ] Logging and monitoring enabled
- [ ] Regular penetration testing
- [ ] Incident response plan
- [ ] Data backup strategy
- [ ] Privacy by design
- [ ] Access control review

## Learning Path

1. OWASP Top 10
2. Secure coding practices
3. Authentication and authorization
4. Cryptography basics
5. Cloud security
6. Compliance frameworks (relevant to domain)
7. Penetration testing (optional)
8. Security architecture

---

[Explore Security on Roadmap.sh](https://roadmap.sh/)