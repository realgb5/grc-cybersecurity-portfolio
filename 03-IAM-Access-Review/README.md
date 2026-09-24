# IAM Access Review

## Overview

A simulated Identity and Access Management (IAM) access review for a fictional financial services organization.

The project demonstrates how a GRC / IT Risk professional can review user access, identify inappropriate or excessive permissions, assess access-related risks, and develop remediation actions.

> **Disclaimer:** This is a simulated portfolio project. All users, systems, approvals, dates, findings, risks, and recommendations are fictional and created for demonstration purposes. This is not a real production access review.

---

## Project Objectives

- Review user and system access
- Validate business justification for access
- Evaluate manager approval and access recertification
- Identify excessive or inappropriate permissions
- Identify privileged-access risks
- Identify segregation-of-duties (SoD) conflicts
- Evaluate identity lifecycle controls
- Assess contractor access
- Prioritize access-related risks
- Develop remediation recommendations

---

## IAM Areas Assessed

The review evaluates several core IAM and access-control practices:

- Least privilege
- Access recertification
- Multi-factor authentication (MFA)
- Privileged access management
- Segregation of duties
- Joiner / mover / leaver controls
- Employee offboarding
- Contractor access
- Access expiration
- Manager approval
- Role-based access

---

## Assessment Methodology

The review followed a simplified IAM access-review workflow:

**User / Role → System Access → Business Need → Approval → Control Check → Finding → Risk → Remediation**

Each sampled access record was evaluated against:

- Business justification
- Manager approval
- MFA status
- Privileged access
- Segregation-of-duties conflicts
- Employment status
- Contractor status
- Access lifecycle requirements

Exceptions were documented, risk-rated, assigned to an owner, and given a remediation timeframe.

---

## Review Scope

### Users Reviewed

**12 simulated user/access records**

### Systems Reviewed

- Core Banking
- ERP
- CRM
- HRIS
- Cloud Platform
- Endpoint Management
- SIEM

### Review Focus

The assessment focused on whether users had appropriate access based on their role and whether access-control processes adequately addressed privileged access, SoD, authentication, and identity lifecycle risks.

---

## Key Findings

The simulated review identified several access-control exceptions:

| Risk Area | Priority | Finding |
|---|---|---|
| Employee Offboarding | Critical | A former employee account remained active |
| Segregation of Duties | Critical | Privileged access created a conflicting responsibility |
| Privileged Access | High | Cloud administrator access exceeded documented job requirements |
| Contractor Access | High | Contractor access did not have a defined expiration |
| Access Recertification | Medium | Manager approval evidence was incomplete |

---

## Risk Assessment

A **5x5 likelihood and impact model** was used to prioritize simulated IAM risks.

**Risk Score = Likelihood × Impact**

Risk ratings include:

- Critical
- High
- Medium
- Low

> The 5x5 scoring model is a portfolio methodology used for this simulation and is not prescribed by a specific IAM standard.

---

## Material Risks

### 1. Active Former-Employee Account

A simulated former employee retained an active CRM account.

**Risk:** Unauthorized access to organizational information.

**Recommended action:**

- Disable the account immediately
- Review recent authentication activity
- Validate the offboarding workflow
- Document remediation

---

### 2. Segregation-of-Duties Conflict

A simulated privileged user had access that conflicted with transaction-approval responsibilities.

**Risk:** A single individual could potentially perform conflicting activities without adequate independent oversight.

**Recommended action:**

- Remove the conflicting entitlement
- Establish independent approval
- Perform a follow-up SoD review

---

### 3. Excessive Privileged Access

A simulated cloud administrator had broader permissions than required for their documented responsibilities.

**Risk:** Excessive administrative privileges increase the potential impact of account compromise or misuse.

**Recommended action:**

- Reduce role scope
- Apply least privilege
- Consider just-in-time privileged access
- Perform periodic privileged-access reviews

---

### 4. Contractor Access Without Defined Expiration

A simulated contractor account did not have a documented access expiration date.

**Risk:** Access may remain active after the business need ends.

**Recommended action:**

- Establish an access expiry date
- Assign a business sponsor
- Automate or track expiration
- Review contractor access periodically

---

## Remediation Roadmap

### Immediate

- Disable the former-employee account
- Review associated authentication activity
- Validate the employee offboarding process

### 0–30 Days

- Resolve segregation-of-duties conflicts
- Reduce excessive privileged access
- Establish contractor access expiration controls

### 31–60 Days

- Standardize periodic access certification
- Improve manager approval evidence
- Strengthen privileged-access review procedures

---

## Deliverables

### 1. IAM Access Review Workbook

The Excel workbook contains:

- Executive dashboard
- Access review population
- Access risk register
- Remediation plan
- IAM control mapping
- Scope and methodology
- References

**[View the IAM Access Review Workbook](./IAM_Access_Review_Portfolio.xlsx)**

### 2. Executive Assessment Report

The PDF report summarizes:

- Executive findings
- Material IAM risks
- Review methodology
- Key control exceptions
- Remediation priorities
- Skills demonstrated

**[View the IAM Executive Assessment Report](./IAM_Access_Review_Executive_Report.pdf)**

---

## Skills Demonstrated

### IAM & IT Risk

- Identity and Access Management
- Access reviews
- Access recertification
- Least privilege
- Privileged access management
- Segregation of duties
- Identity lifecycle management
- Risk assessment
- Risk prioritization
- Remediation planning

### GRC

- Control assessment
- Exception identification
- Risk documentation
- Control ownership
- Remediation tracking
- Executive reporting

### Business & Technical Skills

- Excel-based risk analysis
- Access review documentation
- Risk registers
- Control mapping
- Executive dashboards
- Stakeholder-oriented communication

---

## Project Structure

```text
03-IAM-Access-Review/
│
├── README.md
├── IAM_Access_Review_Portfolio.xlsx
└── IAM_Access_Review_Executive_Report.pdf
