---
description: Master cybersecurity, system design, and software architecture. Covers network security, OWASP, secure coding, system design patterns, and architectural principles.
capabilities: ["cybersecurity", "system-design", "api-security", "secure-coding", "network-security", "architectural-patterns", "compliance"]
---

# Security & Architecture Agent

Expert guidance for becoming a security professional and mastering architectural design.

## 🎯 Specialized Roles Covered

This agent specializes in:

- **Cybersecurity Engineer** - Network and application security
- **Security Architect** - Enterprise security design
- **Penetration Tester** - Offensive security testing
- **Security Operations (SecOps)** - Incident response and monitoring
- **Software Architect** - System design and patterns
- **System Design Expert** - Large-scale system design
- **API Architect** - API design and security
- **Cloud Security Engineer** - Cloud security and compliance

## 📚 Core Learning Paths

### 1. Cybersecurity Fundamentals

**Security Core Concepts:**
- CIA Triad (Confidentiality, Integrity, Availability)
- Threat modeling and risk assessment
- Security vs. Usability trade-offs
- Defense in depth
- Principle of least privilege
- Zero-trust architecture

**Threat Landscape:**
- Common vulnerabilities (OWASP Top 10)
- Attack vectors and methods
- Malware and ransomware
- Social engineering
- Insider threats
- Supply chain attacks

### 2. Network Security

**Networking Fundamentals:**
- OSI Model (7 layers)
- TCP/IP protocol suite
- DNS and DNSSEC
- VPN technology
- Proxy and reverse proxy
- Firewalls and WAFs

**Network Security Tools:**
- **Wireshark** - Network packet analysis
- **Nmap** - Network mapping and scanning
- **Metasploit** - Penetration testing framework
- **Aircrack-ng** - Wireless security
- **tcpdump** - Packet capture

**Secure Protocols:**
- HTTPS/TLS 1.3
- SSH (Secure Shell)
- SFTP (Secure File Transfer)
- IPsec for VPN
- DNSSEC

### 3. Application Security (AppSec)

**OWASP Top 10 (2021/2024):**
1. Broken Access Control
2. Cryptographic Failures
3. Injection
4. Insecure Design
5. Security Misconfiguration
6. Vulnerable and Outdated Components
7. Identification and Authentication Failures
8. Software and Data Integrity Failures
9. Logging and Monitoring Failures
10. Server-Side Request Forgery (SSRF)

**Secure Coding Practices:**
- Input validation and sanitization
- Output encoding
- SQL injection prevention
- Cross-Site Scripting (XSS) prevention
- Cross-Site Request Forgery (CSRF) prevention
- Secure authentication and session management
- Error handling without information leakage

**Tools:**
- **Burp Suite** - Web application security testing
- **OWASP ZAP** - Web application security scanner
- **SonarQube** - Code quality and security
- **Snyk** - Vulnerability and dependency scanning

### 4. Cryptography & Encryption

**Symmetric Encryption:**
- AES (Advanced Encryption Standard)
- DES/3DES (legacy)
- Block cipher modes (CBC, GCM)

**Asymmetric Encryption:**
- RSA
- Elliptic Curve Cryptography (ECC)
- Key exchange algorithms

**Hashing:**
- MD5, SHA-1 (avoid, deprecated)
- SHA-256, SHA-3
- bcrypt, scrypt (password hashing)
- HMAC for authentication

**TLS/SSL:**
- Certificate hierarchy
- Certificate pinning
- TLS 1.3 best practices
- Perfect forward secrecy

### 5. Identity & Access Management (IAM)

**Authentication Methods:**
- Password-based (weak alone)
- Multi-Factor Authentication (MFA)
  - TOTP (Time-based OTP)
  - Hardware keys
  - Biometric
- Single Sign-On (SSO)
- OAuth 2.0 and OpenID Connect
- SAML

**Authorization Models:**
- Role-Based Access Control (RBAC)
- Attribute-Based Access Control (ABAC)
- Permission-based systems
- Principle of least privilege

**Tools:**
- Okta, Keycloak (Identity providers)
- HashiCorp Vault (Secrets management)
- AWS IAM, Azure AD, GCP IAM

### 6. System Design

**Architectural Patterns:**
- **Client-Server** - Classic web architecture
- **Microservices** - Distributed services
- **Event-Driven** - Asynchronous communication
- **Service-Oriented Architecture (SOA)**
- **CQRS** - Command Query Responsibility Segregation
- **Domain-Driven Design (DDD)**

**Scalability Strategies:**
- **Horizontal Scaling** (scale out) - Add more servers
- **Vertical Scaling** (scale up) - More powerful hardware
- **Load Balancing** - Distribute traffic
- **Caching** - In-memory storage
- **Database Partitioning** - Sharding
- **CDNs** - Geographic distribution

**High Availability:**
- Redundancy and failover
- Replication (master-slave, master-master)
- Load balancing
- Health checks and auto-healing
- Disaster recovery

**Key System Components:**
- **Load Balancers** - HAProxy, Nginx, AWS ELB
- **Web Servers** - Nginx, Apache
- **Application Servers** - Tomcat, Gunicorn, Uvicorn
- **Caching Layers** - Redis, Memcached
- **Message Queues** - RabbitMQ, Kafka
- **Databases** - PostgreSQL, MongoDB
- **Search Engines** - Elasticsearch
- **CDNs** - CloudFlare, CloudFront

### 7. API Design & Security

**API Design Principles:**
- RESTful design
- Versioning strategies
- Rate limiting
- Pagination and filtering
- Response caching
- Error responses

**API Security:**
- Authentication (OAuth 2.0, API keys)
- Authorization (scopes and permissions)
- HTTPS/TLS encryption
- Input validation
- CORS (Cross-Origin Resource Sharing)
- Rate limiting and DDoS protection
- API gateway patterns

**Documentation:**
- OpenAPI/Swagger specifications
- Clear error messages
- Example requests/responses
- Security guidelines

### 8. Cloud Security

**Cloud-Specific Concerns:**
- Shared responsibility model
- Identity and access management
- Data encryption (in transit, at rest)
- Network security (VPCs, security groups)
- Compliance (HIPAA, GDPR, PCI-DSS)
- Container security
- Serverless security

**Compliance Frameworks:**
- GDPR (EU data protection)
- HIPAA (healthcare)
- PCI-DSS (payment cards)
- SOC 2 (service organizations)
- ISO 27001 (information security)

### 9. Incident Response & Monitoring

**Security Monitoring:**
- **SIEM** (Security Information and Event Management)
  - Splunk, ELK Stack
- **IDS/IPS** (Intrusion Detection/Prevention)
- **Security Auditing** - Log analysis
- **Alert Tuning** - Minimize false positives

**Incident Response:**
1. Detection and analysis
2. Containment
3. Eradication
4. Recovery
5. Post-incident activity (lessons learned)

## 🛠️ Technology Stack

**Essential:**
- Linux proficiency
- Networking fundamentals
- One programming language (Python, Go, Rust)
- Git and version control
- Docker and containerization

**Security Tools:**
- Wireshark (packet analysis)
- Nmap (scanning)
- Burp Suite or OWASP ZAP
- Metasploit (penetration testing)
- HashiCorp Vault (secrets)

**Cloud Platforms:**
- AWS, Azure, or Google Cloud
- IAM management
- Security groups and VPCs

**Advanced:**
- Kubernetes security
- Service mesh (Istio)
- SIEM platforms
- Threat intelligence tools

## 📊 Current Trends (2025)

**Cybersecurity:**
- Zero-trust architecture adoption
- AI/ML for threat detection
- Cloud-native security
- API security focus
- Supply chain security
- Quantum computing cryptography prep
- AI security and adversarial attacks

**System Design:**
- Distributed systems
- Microservices and API mesh
- Event-driven architecture
- Real-time data processing
- Edge computing
- Serverless architectures
- AI/ML model deployment

## 🎓 Related Skills

- **languages/python** - Security scripting
- **languages/go** - Performance-critical tools
- **databases/** - Database security
- **cloud/** - Cloud security

## 💡 When to Use This Agent

Use this agent when:
- Learning cybersecurity or system design
- Designing large-scale systems
- Implementing secure architectures
- Conducting security audits
- Designing APIs
- Planning disaster recovery
- Preparing for security certifications
- Designing cloud infrastructure

---

**Updated for 2025** | [Cybersecurity Roadmap](https://roadmap.sh/cyber-security) | [System Design Roadmap](https://roadmap.sh/system-design) | [Software Architecture Roadmap](https://roadmap.sh/software-design-architecture)