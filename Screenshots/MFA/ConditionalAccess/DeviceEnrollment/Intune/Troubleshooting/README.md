# Troubleshooting 
1. User Cannot Sign In
Problem

Test.Employee receives:

"Your account or password is incorrect."

Troubleshooting Steps
Verify account exists in Entra ID
Check Block Sign-In status
Reset password
Review Sign-In Logs
Test login again
Document
Symptoms
Root Cause
Resolution
Screenshot of Sign-In Logs
2. MFA Prompt Not Appearing
Problem

User signs in but MFA is never requested.

Troubleshooting Steps
Check Conditional Access assignment
Verify user is in targeted group
Review Policy Insights
Confirm policy is enabled
Re-test login
Root Cause Example

User was not a member of the MFA group.

Skills Demonstrated
Conditional Access
Entra Groups
MFA
3. Conditional Access Blocking User
Problem

User cannot access Microsoft 365.

Error:

Access has been blocked by Conditional Access policy.

Troubleshooting
Review Sign-In Logs
Check Conditional Access tab
Identify triggered policy
Verify exclusions
Test with report-only mode
Screenshot Ideas
Sign-in logs
CA policy
Policy assignments
4. License Assigned but Apps Missing
Problem

User has a Business Premium license but cannot access Teams.

Troubleshooting
Verify license assignment
Check Apps and Service Plans
Confirm Teams service enabled
Force sign-out/in
Root Cause

Teams service plan disabled.

5. Device Not Enrolling into Intune
Problem

Laptop shows:

Not managed

Troubleshooting
Verify user licensed
Check MDM authority
Verify enrollment scope
Confirm Azure AD joined
Screenshots
Entra device
Enrollment settings
Intune devices
6. Device Becomes Non-Compliant
Problem

Device blocked from company resources.

Troubleshooting
Review Compliance Policy
Check Device Compliance Report
Update device settings
Sync device
Root Cause Examples
BitLocker disabled
OS version outdated
Antivirus off
7. Group-Based Licensing Not Working
Problem

User added to DG-Employees group but receives no license.

Troubleshooting
Verify license assigned to group
Check processing status
Review group membership
Confirm available licenses
Demonstrates
Entra ID Groups
Group-Based Licensing
8. User Not Receiving Intune Policy
Problem

Settings profile isn't applied.

Troubleshooting
Check assignment group
Verify device membership
Sync device
Check Device Configuration Status
Screenshots
Assignment configuration
Deployment status
9. Break Glass Account Validation
Problem

Verify emergency account works during outage.

Testing
Confirm CA exclusions
Verify MFA exclusions
Test sign-in
Document outcome
Demonstrates
Security best practices
Business continuity
10. Investigating Risky Sign-In
Problem

Suspicious login detected.

Troubleshooting
Review Sign-In Logs
Check location
Review device information
Determine legitimate vs suspicious activity
Take action if needed
Demonstrates
Identity Protection
Security Operations
Incident Response
