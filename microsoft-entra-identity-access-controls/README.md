# Microsoft Entra ID — Identity and Access Controls Review

## 1. Project Overview

This hands-on project demonstrates an identity and access management (IAM) controls review using Microsoft Entra ID. The assessment focused on directory role assignments, group memberships, Azure Role-Based Access Control (RBAC), enterprise application access, authentication methods, and multifactor authentication (MFA) sign-in evidence.

The objective was to identify potential access-control risks, document findings, and recommend security improvements based on the evidence available in the lab environment.

## 2. Project Objectives

- Review privileged directory roles and administrative access.
- Assess user access through directory roles and group memberships.
- Examine Azure RBAC assignments within the reviewed subscription scope.
- Review enterprise application assignments.
- Verify registered authentication methods.
- Examine sign-in logs for MFA authentication evidence.
- Identify potential access-control risks and recommend improvements.

## 3. Tools and Technologies

- Microsoft Entra admin center
- Microsoft Authenticator
- Microsoft Entra sign-in logs
- GitHub for project documentation and evidence management

## 4. Assessment Scope

The review focused on Lab User 01 and the information available in the following areas:

- Directory role assignments
- Group memberships
- Enterprise application assignments
- Azure RBAC assignments for the selected subscription
- Registered authentication methods
- Sign-in authentication details

## 5. Findings and Remediation

| Control Area | Observation | Risk / Impact | Recommended Action |
|---|---|---|---|
| Privileged Access | Reviewed Global Administrator assignments. | Excessive administrative privileges could increase the impact of account compromise. | Review privileged role assignments regularly and enforce least privilege. |
| Directory Roles | No directly assigned directory roles were identified for Lab User 01 in the reviewed view. | Access may be granted through other roles or assignment paths not covered by this review. | Validate effective access and review all relevant role assignments. |
| Group Membership | No group memberships were identified for Lab User 01 in the reviewed view. | Required or inappropriate access may go unnoticed if group access is not reviewed. | Compare group membership against documented business responsibilities. |
| Azure RBAC | No role assignments were found for the selected subscription. | Access at other subscriptions, resource groups, or resource scopes was not assessed by this observation. | Review role assignments at all relevant scopes. |
| Enterprise Applications | No application assignments were found for Lab User 01 in the reviewed view. | Application access may exist through other access mechanisms or remain outside the review scope. | Validate application assignments and access requirements. |
| Authentication | Microsoft Authenticator was registered, and sign-in evidence showed successful MFA completion. | A registered method and one successful MFA event do not prove MFA is enforced for every sign-in. | Review applicable MFA policies and authentication requirements. |

## 6. Key Risks and Recommendations

### Least Privilege
Grant users only the access required to perform their responsibilities. Review privileged access regularly and ensure administrative assignments are justified.

### Access Governance
Validate directory roles, group memberships, application assignments, and Azure RBAC permissions against approved business requirements.

### Multifactor Authentication
Enforce appropriate MFA requirements, especially for privileged accounts. Periodically review registered authentication methods and authentication policies.

### Monitoring and Logging
Review sign-in logs for suspicious activity, unusual authentication patterns, and potential access anomalies.

### Documentation and Review
Document control observations, supporting evidence, remediation recommendations, responsible owners, and review dates.

## 7. Evidence and Screenshots

Supporting screenshots are stored in the project directory and document the reviewed access-control settings and authentication evidence.

Evidence includes:

- Global Administrator assignments
- Lab User 01 directory roles
- Lab User 01 group memberships
- Enterprise application assignments
- Azure role assignments
- Registered authentication methods
- Sign-in logs and MFA authentication details

Refer to the screenshots in the `screenshots/` folder for supporting evidence.

## 8. Limitations

This was a personal learning lab, not a production security audit. Findings reflect the views, permissions, and subscription information available during the assessment.

The absence of assignments in a reviewed view does not establish that no access exists elsewhere in the tenant or at other resource scopes. The assessment does not independently establish that all tenant-wide security policies are configured correctly.

## 9. Skills Demonstrated

- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Privileged access review
- Least-privilege principles
- Access governance and control assessment
- Multifactor authentication (MFA) verification
- Sign-in log analysis
- Access-control risk identification
- Security recommendations and documentation
- Evidence-based assessment and reporting

## 10. Conclusion

This hands-on project demonstrated a structured review of identity and access management controls using Microsoft Entra ID. The assessment examined privileged directory roles, group memberships, Azure Role-Based Access Control (RBAC), enterprise application assignments, registered authentication methods, and sign-in evidence.

The review documented the access information available within the lab environment, identified potential access-control risks, and developed recommendations based on least privilege, appropriate administrative access, periodic access reviews, and multifactor authentication (MFA).

This project strengthened practical skills in IAM controls assessment, access governance, evidence documentation, risk identification, and security remediation recommendations.

**Assessment Limitation:** This was a personal learning lab, not a production security audit. Conclusions are limited to the views, permissions, subscription scope, and evidence available during the review.
