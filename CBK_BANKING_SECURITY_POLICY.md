# Central Bank of Kenya (CBK) Banking Security Policy

**Version:** 1.0  
**Compliance Standard:** CBK Banking Guidelines  
**Effective Date:** October 2026

## 1. Regulatory Requirement

This policy ensures compliance with Central Bank of Kenya cybersecurity guidelines for banking institutions.

## 2. Network Security

### 2.1 Firewalls and Segmentation
- Deploy firewalls at network perimeter
- Segment customer data from operations
- Isolate payment systems
- Segment by function and sensitivity

### 2.2 Intrusion Detection
- Deploy IDS/IPS systems
- Monitor for suspicious activity
- Alert on breach attempts
- Daily log review

### 2.3 VPN Requirements
- Encrypt remote access
- Strong authentication (MFA)
- Session timeout (30 minutes)
- Access logging required

## 3. Authentication & Access Control

### 3.1 Customer Authentication
- Multi-factor authentication for accounts
- Impossible password + something you have
- Biometric as additional factor
- Minimum 12-character passwords

### 3.2 Employee Access Control
- Role-based access control (RBAC)
- Principle of least privilege
- Segregation of duties for payments
- Quarterly access reviews

### 3.3 Administrative Access
- Separate admin accounts
- Multi-approval for sensitive changes
- Monitoring of admin activities
- Audit trails immutable

## 4. Encryption Standards

### 4.1 Data in Transit
- TLS 1.2 minimum (TLS 1.3 recommended)
- Strong cipher suites only
- Certificate pinning for APIs
- Perfect forward secrecy

### 4.2 Data at Rest
- AES-256 for customer data
- Separate encryption keys
- Key rotation every 2 years
- Key backup and recovery procedures

### 4.3 Payment Data
- PCI DSS compliance minimum
- End-to-end encryption for transactions
- Tokenization of sensitive data
- Minimal storage of card data

## 5. Transaction Security

### 5.1 Transaction Limits
- Per-transaction limits enforced
- Daily transfer limits
- Number of transactions per day
- Escalation for high-value transfers

### 5.2 Transaction Monitoring
- Real-time fraud detection
- Pattern analysis
- Velocity checks
- Anomaly alerts

### 5.3 Transaction Approval
- Dual control for large transfers
- Time-based approval windows
- Approval workflow logging
- Reconciliation procedures

## 6. System Security

### 6.1 Patch Management
- Critical patches: Within 7 days
- High: Within 30 days
- Medium: Within 90 days
- Low: Within 180 days
- Test before production deployment

### 6.2 Vulnerability Management
- Quarterly vulnerability scanning
- Annual penetration testing
- Remediation tracking
- Risk assessment for findings

### 6.3 System Monitoring
- 24/7 monitoring
- Real-time alerting
- Incident response team on-call
- Performance baselines

## 7. Backup and Recovery

### 7.1 Backup Requirements
- Daily encrypted backups
- Off-site backup storage
- Backup testing monthly
- Recovery time objective (RTO): 4 hours
- Recovery point objective (RPO): 1 hour

### 7.2 Disaster Recovery
- DR plan documented
- Annual DR testing
- Failover procedures
- Alternative processing site

### 7.3 Business Continuity
- BCP for critical functions
- Third-party dependencies mapped
- Vendor SLAs documented
- Crisis communication plan

## 8. Incident Response

### 8.1 Incident Reporting
- Report to CBK immediately
- Document incident timeline
- Preserve evidence
- Stakeholder notification

### 8.2 Incident Classification
- **Critical:** System outage, fraud >100M KES
- **High:** Partial outage, fraud 10-100M KES
- **Medium:** Limited impact incidents
- **Low:** Informational findings

### 8.3 Regulatory Reporting
- CBK: Within 24 hours for critical
- Customers: As appropriate
- Press release if material

## 9. Staff Training

### 9.1 Security Awareness
- Annual training mandatory
- New hire training within 30 days
- Phishing simulations quarterly
- Training tracking and documentation

### 9.2 Role-Specific Training
- Developers: Secure coding
- Administrators: Access control
- Operations: Incident response
- Customers: Security best practices

## 10. Third-Party Management

### 10.1 Vendor Assessment
- Security questionnaire
- On-site audits for critical vendors
- Compliance certification review
- Financial stability check

### 10.2 Vendor Agreements
- SLAs documented
- Security requirements specified
- Incident notification terms
- Right to audit included

### 10.3 Vendor Monitoring
- Annual compliance reviews
- Incident reporting requirements
- Change notification process
- Sub-processor controls

## 11. Compliance Verification

### 11.1 Internal Audit
- Quarterly compliance checks
- Annual IT audit
- Findings tracking
- Remediation verification

### 11.2 External Audit
- Annual external audit
- Penetration test annually
- Compliance certification
- Regulatory exam participation

### 11.3 Regulatory Requirements
- CBK examination participation
- Compliance questionnaires
- Incident notification
- Policy updates submission

---

**Approval Date:** ________________  
**Chief Information Officer:** ________________  
**Chief Risk Officer:** ________________  
**CEO:** ________________
