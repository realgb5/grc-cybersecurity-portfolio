Microsoft Entra ID — Identity and Access Controls Review
Project Overview
This project demonstrates a practical review of identity and access controls using Microsoft Entra ID. The lab examines privileged directory roles, user group memberships, Azure role assignments, enterprise application access, authentication methods, and multifactor authentication (MFA) sign-in evidence.
Objectives
Review privileged role assignments and administrative access.
Assess user access through directory roles and group memberships.
Review Azure RBAC and enterprise application assignments.
Verify registered authentication methods.
Examine sign-in logs for MFA authentication evidence.
Identify potential access-control risks and recommend improvements.
Tools and Technologies
Microsoft Entra admin center
Microsoft Authenticator
Microsoft Entra sign-in logs
GitHub for project documentation
Evidence and Findings
Control area
Observation
Privileged access
Reviewed Global Administrator role assignments.
Directory roles
Lab User 01 had no directly assigned directory roles in the reviewed view.
Group membership
Lab User 01 was not a member of any groups in the reviewed view.
Azure RBAC
No role assignments were found for the selected subscription.
Application access
No application assignments were found for the lab user.
Authentication
Microsoft Authenticator was registered.
MFA verification
Sign-in authentication details showed successful MFA completion evidence.
Security Recommendations
Apply least privilege and avoid unnecessary Global Administrator assignments.
Review privileged access regularly and document business justification.
Enforce appropriate MFA requirements for users, especially privileged accounts.
Review sign-in logs for suspicious activity and authentication anomalies.
Periodically validate group memberships, application access, and Azure RBAC assignments.
Document access-review findings, remediation owners, and review dates.
Limitations
This is a personal learning lab, not a production security audit. Findings reflect the views and subscription available during the review. The lab does not establish that every tenant-wide security policy is configured correctly.
Screenshots
Evidence screenshots are stored in the screenshots/ folder.
Skills Demonstrated
Identity and Access Management (IAM), Role-Based Access Control (RBAC), privileged access review, least privilege, MFA verification, sign-in log analysis, access-control documentation, and security recommendations.
