# PERSONAL SECURITY AUDIT REPORT
Auditor: Pratyaksha Mishra
Audit Date: 2026-07-26
Engagement: Personal Digital Security Assessment
Methodology: Scope > Intelligence > Exposure > Severity > Remediation

1. SCOPE
Systems and accounts assessed:

Primary email: [Praty1927@gmail.com]

Key accounts: Google, University Portal, LinkedIn, GitHub, Internshala

Primary device: [Andriod, Windows Laptop]

Network: Sunil_5GHz

2. EXECUTIVE SUMMARY
Assessment confirmed a clean status with zero recorded breaches on HaveIBeenPwned, indicating a strong baseline for digital hygiene. The primary security focus was hardening the "master key" (primary Google account) against potential threats by upgrading authentication methods. One critical remediation action was completed, and a monitoring plan has been established for ongoing footprint management.

3. FINDINGS
CRITICAL
[x] Primary email (Google) previously relied on SMS-based 2FA (upgraded to Authenticator App).

HIGH
[ ] No suspicious active sessions identified on primary Google account.

MEDIUM
[ ] Multiple third-party apps connected to Google account (pending periodic audit).
[ ] Primary email searchable via OSINT tools (basic identity information visible).

LOW
[ ] Minimal exposure; no forgotten accounts identified as high-risk during audit.

4. ACTIONS TAKEN DURING AUDIT
[x] Enabled app-based 2FA on primary Google account using Google Authenticator.
[x] Verified time-sync synchronization for 2FA token generation.
[x] Confirmed zero-breach status via HaveIBeenPwned audit.

5. REMEDIATION PLAN
This week:
[ ] Generate and store physical backup codes for Google 2FA.
[ ] Review "Third-party apps with account access" in Google settings and remove unused permissions.

This month:
[ ] Audit active sessions across secondary accounts (LinkedIn/GitHub).
[ ] Implement a password manager for high-value accounts if not already in use.

END OF REPORT