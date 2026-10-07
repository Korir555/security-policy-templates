# Password Security Policy

**Version:** 1.0  
**Effective Date:** October 2026  
**Organization:** [Your Organization]

## 1. Purpose

This policy establishes standards for password creation, management, and security to protect organizational systems and data.

## 2. Password Requirements

### 2.1 Minimum Standards

All system passwords must meet:
- **Length:** Minimum 12 characters
- **Complexity:** Mix of:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters (!@#$%^&*)
- **No Dictionary Words:** Cannot contain common words or names
- **No Personal Information:** Cannot contain user's name, username, or birthdate

### 2.2 Examples

✓ **STRONG:** `Tr0p!cal$unSet#2026`  
✗ **WEAK:** `password123` (dictionary word, no special chars)  
✗ **WEAK:** `MyName2026` (contains personal information)

### 2.3 Password Changes

- Initial password must be changed at first login
- System passwords changed every 90 days
- Admin passwords changed every 30 days
- Cannot reuse last 5 passwords
- Force password change after compromise

## 3. Multi-Factor Authentication (MFA)

### 3.1 Mandatory MFA

MFA required for:
- Administrative accounts (critical)
- Financial/payment systems (critical)
- Customer data access (high)
- VPN access (high)
- Email accounts (medium)

### 3.2 MFA Methods

Accepted MFA methods:
1. Time-based one-time password (TOTP) - Google Authenticator, Authy
2. Hardware token - YubiKey, security key
3. SMS text message (if TOTP unavailable) - secondary only
4. Biometric (fingerprint, facial recognition)

### 3.3 MFA Recovery

- Backup recovery codes stored securely
- Recovery procedure documented
- Account lockout after failed attempts (5 tries)

## 4. Password Management

### 4.1 Password Managers

**Recommended:** Use organizational password manager (LastPass, 1Password, Dashlane)

- Centralized, encrypted storage
- Strong password generation
- Automatic filling for authorized sites
- Audit trail of access

### 4.2 Practices

**DO:**
- Use password manager to generate/store passwords
- Use unique password for each system
- Store recovery codes securely
- Lock screen when away from desk

**DON'T:**
- Write passwords on paper or sticky notes
- Share passwords via email or chat
- Reuse passwords across systems
- Use browser password storage for sensitive accounts
- Store passwords in plain text files

## 5. Shared Account Management

### 5.1 Shared Accounts Discouraged

Avoid shared accounts. Use individual accounts with appropriate access levels instead.

### 5.2 When Necessary

If shared accounts required:
- Documented business justification
- Approval from manager and security
- Quarterly access review
- Immediate rotation on employee departure
- Audit logging of all access
- No multi-factor authentication bypass

## 6. Privileged Account Management

### 6.1 Admin/Root Account Policies

- Never use admin account for regular work
- Separate regular user account from admin account
- Admin access approved and logged
- Session timeout after 30 minutes of inactivity
- Mandatory MFA for all admin accounts

### 6.2 Privileged Access Workstation

Admin access only from:
- Dedicated workstation (if possible)
- Hardened system with security controls
- Network-isolated if handling critical systems
- Monitored for all activity

## 7. Password Reset Procedures

### 7.1 User-Initiated Reset

- Secure password reset link via email
- Link expires after 1 hour
- Must answer security questions OR enter previous password
- System confirms identity before allowing reset
- Audit log of reset attempt

### 7.2 Admin-Initiated Reset

- Manager approves reset
- Temporary password generated
- User must change at next login
- Documented in ticket system
- Notification to user of reset

## 8. Account Lockout

### 8.1 Lockout Triggers

Account locks after:
- 5 failed login attempts
- Password expiration (must reset to unlock)
- Admin lockdown for security incident
- Unused for 90 days (inactive accounts)

### 8.2 Unlock Procedures

- Self-service unlock via security questions
- Help desk verification and unlock (max 1 hour)
- Audit log of unlock request
- Notification to account owner

## 9. Compliance Verification

- Monthly password policy audits
- Quarterly MFA compliance check
- Annual shared account review
- Detect weak passwords via scanning
- Incident investigation for breaches

## 10. Violations & Consequences

- First violation: Written warning + retraining
- Repeated violations: Account suspension + disciplinary action
- Severe violations (password sharing, credential storage): Up to termination

---

**Policy Owner:** Chief Information Security Officer  
**Approval:** _________________ Date: _______
