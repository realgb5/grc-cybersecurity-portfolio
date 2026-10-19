Microsoft Entra ID — Identity and Access Controls Review
1. Project Overview
This project demonstrates a hands-on review of identity and access controls using Microsoft Entra ID. The assessment examines directory roles, group memberships, Azure Role-Based Access Control (RBAC), enterprise application access, authentication methods, and sign-in evidence.
2. Objectives
Review privileged directory role assignments and administrative access.
Assess user access through directory roles and group memberships.
Review Azure RBAC and enterprise application assignments.
Verify registered authentication methods.
Examine sign-in logs for multifactor authentication (MFA) evidence.
Identify potential access-control risks and recommend improvements.
3. Tools and Technologies
Microsoft Entra admin center
Microsoft Authenticator
Microsoft Entra sign-in logs
GitHub for documentation and evidence
4. Assessment Scope
The review focused on Lab User 01, available directory-role assignment views, group memberships, application assignments, Azure role assignments for the selected subscription, registered authentication methods, and sign-in authentication details.
5. Findings and Observations
Control Area
Observation
Privileged access
Global Administrator role assignments were reviewed.
Directory roles
No directly assigned directory roles were identified for Lab User 01 in the reviewed view.
Group membership
Lab User 01 was not a member of any groups in the reviewed view.
Azure RBAC
No role assignments were found for the selected subscription.
Application access
No application assignments were found for Lab User 01.
Authentication methods
Microsoft Authenticator was registered on an iPhone.
MFA verification
Sign-in authentication details showed successful MFA completion evidence.
6. Risks and Recommendations
Potential risk: Excessive privileged access
Apply least-privilege principles.
Review privileged directory roles regularly.
Ensure administrative access is justified and appropriately controlled.
Potential risk: Inappropriate or missing access
Confirm that user access aligns with job responsibilities.
Validate group memberships and application assignments against business requirements.
Review Azure RBAC assignments at relevant scopes.
Authentication security
Enforce appropriate MFA requirements.
Review sign-in logs for suspicious activity and authentication anomalies.
Periodically validate registered authentication methods.
7. Evidence and Screenshots
Supporting screenshots are stored in the screenshots/ folder. They document the reviewed directory roles, group memberships, application assignments, Azure role assignments, authentication methods, and sign-in evidence.
8. Limitations
This was a personal learning lab, not a production security audit. Findings reflect the views and subscription available during the assessment. The absence of assignments in a reviewed view does not establish that no access exists elsewhere in the tenant or at other resource scopes.
9. Skills Demonstrated
Identity and Access Management (IAM)
Role-Based Access Control (RBAC)
Privileged access review
Multifactor authentication (MFA) verification
Sign-in log analysis
Access-control risk identification
Security recommendations and documentation
GitHub project documentation
