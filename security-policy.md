# QAQuest Security Policy

Last updated: 2026-06-09

## 1. Overview

QAQuest is committed to protecting customer and End-User Data through secure-by-design practices aligned with Atlassian Marketplace security requirements.

This policy describes how we handle:
- security controls,
- vulnerability reporting,
- incident response,
- responsible disclosure.

## 2. Scope

This policy applies to:
- QAQuest cloud app components,
- source code and build/deployment pipelines under QAQuest control,
- operational processes used to maintain app security.

## 3. Security Principles

We follow these core principles:

1. Least privilege  
   We request and use only the permissions required for app functionality.

2. Data minimization  
   We process only data necessary to deliver the service.

3. Defense in depth  
   We combine preventive, detective, and corrective controls across code, infrastructure, and operations.

4. Secure development lifecycle  
   We use code review, dependency checks, and security validation before release.

5. Continuous improvement  
   We periodically review controls and update processes based on risk and change.

## 4. Data Protection

- End-User Data is handled according to our Privacy Policy and applicable laws.
- QAQuest does not require customers to share Atlassian account passwords or personal access tokens (PATs) for normal app functionality.
- Logging is limited to operational troubleshooting and reliability needs, with efforts to avoid unnecessary sensitive content.

## 5. Vulnerability Management

- We perform vulnerability assessments, including dependency/security scanning.
- Findings are triaged by severity and remediated according to risk.
- Critical/high-risk issues are prioritized for expedited resolution.

## 6. Security Incident Response

If a confirmed security incident affects QAQuest, we will:
1. contain and investigate the issue,
2. remediate root cause,
3. notify affected parties and Atlassian when required,
4. document lessons learned and improve controls.

## 7. Responsible Disclosure

We welcome responsible vulnerability reports from researchers and customers.

Please include, when possible:
- affected component/feature,
- reproduction steps,
- impact assessment,
- proof-of-concept (non-destructive).

Do not:
- access or modify customer data without permission,
- disrupt service availability,
- perform destructive testing.

## 8. Security Contact

For security issues, contact: **jta@cin.ufpe.br**  

We will acknowledge receipt of security reports as quickly as reasonably possible.

## 9. Third-Party Components

QAQuest uses third-party libraries and dependencies as part of normal development.  
We monitor and update these components to address known vulnerabilities and reduce supply-chain risk.

## 10. Policy Updates

We may update this policy periodically to reflect product, legal, or operational changes.  
Material updates will be published in this repository.
