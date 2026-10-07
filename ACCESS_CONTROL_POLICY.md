# Access Control Policy

**Version:** 1.0  
**Effective Date:** October 2026  
**Organization:** [Your Organization]

## 1. Purpose

This policy establishes access control standards to ensure only authorized users access appropriate systems and data.

## 2. Access Control Principles

### 2.1 Principle of Least Privilege

Users receive minimum access necessary to perform their job duties.

- Every access request must have documented business justification
- Access is role-based, not individual preferences
- Excess access is a security risk and compliance violation

### 2.2 Segregation of Duties

Conflicting duties separated to prevent fraud:
- Cannot approve own access requests
- Cannot approve own financial transactions
- Cannot access sensitive data they authorize
- Cannot override security controls they manage

### 2.3 Role-Based Access Control (RBAC)

Access determined by job role:
- **Role Definition:** Job responsibilities and required systems
- **Role Assignment:** Manager assigns appropriate role
- **Access Rights:** System grants access based on role
- **Quarterly Review:** Access relevance verified every 3 months

## 3. Access Request Procedure

### 3.1 Request Submission

1. Employee submits access request via ticketing system
2. Form includes:
   - System/resource needed
   - Business justification
   - Required access level
   - Duration (temporary vs. permanent)
   - Manager name for approval

### 3.2 Manager Approval

Manager verifies:
- Access needed for current role
- Justification is appropriate
- Access level matches responsibility
- No conflicts with other duties

### 3.3 System Administrator Action

Admin verifies:
- User identity in directory
- No access conflicts
- Role has access to resource
- Implements appropriate access controls

### 3.4 Completion & Logging

- User notified of access grant
- Audit log created automatically
- Access recorded in access control matrix
- Scheduled for quarterly review

## 4. System Accounts

### 4.1 Individual Accounts Required

- One account per person
- Account linked to legal name and employee ID
- Unique username (firstname.lastname format)
- Disable shared accounts

### 4.2 Service Accounts

Accounts for system-to-system communication:
- Named after service: service-account-[name]
- No human user associated
- Credential rotation every 90 days
- Activity logging and monitoring
- Limited to specific systems/APIs

### 4.3 Admin/Root Accounts

- Separate from regular user account
- Used only for administrative functions
- Strong MFA required (hardware token preferred)
- Session timeout: 30 minutes
- Every action logged

## 5. Onboarding Access

### 5.1 New Employee Process

**Day 1 (Before Start):**
- Set role in directory
- Assign RBAC groups
- Provision required access

**First Week:**
- Verify all systems accessible
- Test access to required resources
- Provide access documentation

**30 Days:**
- Verify access still appropriate
- Update if role changed
- Document any issues

### 5.2 Role Changes

When employee changes role:
- Notify system administrators
- Remove previous role access
- Assign new role access
- Update access control matrix
- Document reason for change

## 6. Offboarding Access Removal

### 6.1 Termination Process

**Last Day:**
- Disable all system accounts
- Revoke API keys and tokens
- Retrieve access badges/keys
- Collect equipment

**Within 24 Hours:**
- Delete accounts from systems
- Archive account data (if required)
- Audit log of all removals

### 6.2 Leave of Absence

**Extended leave (>30 days):**
- Disable email access
- Disable VPN access
- Remove sensitive data access
- Maintain other access (reinstate on return)

**Return from leave:**
- Reactivate disabled access
- Verify role still valid
- Confirm password still secure

## 7. Access Review

### 7.1 Quarterly Review

Every 90 days:
- Manager reviews employee access
- Verify access matches current role
- Identify and remove excess access
- Document review completion

### 7.2 Role-Based Review

Quarterly review of each role:
- Verify systems in role are appropriate
- Identify additions/removals needed
- Document changes
- Communicate to affected users

### 7.3 Annual Comprehensive Review

Annually:
- Full access control matrix audit
- Identify dormant accounts
- Verify all accounts active
- Clean up unused accounts
- Report to leadership

## 8. Privileged Access Management

### 8.1 Elevated Access Request

Requests for admin/root access:
- Submitted before needed
- Business justification required
- Manager approval mandatory
- Security approval required
- Time-limited (1 day, 1 week, or 1 month)
- Automatic revocation on expiration

### 8.2 Privileged Session Monitoring

When privileged access granted:
- Session recording/logging
- Keyboard/screen capture
- Command logging
- Real-time alerts for unusual activity
- Audit trail of all actions

## 9. Third-Party Access

### 9.1 Vendor/Contractor Access

- Require signed contractor agreement
- Limited to required systems only
- Time-limited (contract end date)
- Removed on contract termination
- No system administrator access
- Monitored separately from employees

### 9.2 Partner Integration

- API keys for integration
- Rate limiting enforced
- IP address whitelisting
- Access logging
- Quarterly review with partner

## 10. Audit Logging

All access activity logged:
- User ID and timestamp
- System/resource accessed
- Action performed
- Success/failure status
- Source IP address
- Retention: Minimum 12 months

## 11. Access Control Exceptions

### 11.1 Exception Process

For access that doesn't fit policy:
- Document business justification
- Manager approval required
- Security exception approval required
- Compensating controls implemented
- Quarterly review
- Documented in exception register

### 11.2 Emergency Access

For critical system outages:
- Business manager authorizes
- Temporary access granted
- Session recorded/monitored
- Removed within 24 hours
- Post-incident review

## 12. Compliance Verification

- Monthly access reports
- Quarterly access reviews
- Annual comprehensive audit
- Penetration testing (includes access testing)
- Compliance assessment

---

**Policy Owner:** Chief Information Security Officer  
**Approval:** _________________ Date: _______
