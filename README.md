# NovaPay AWS Security Assessment

NovaPay Finance is a financial services organization that uses AWS to support its cloud environment and protect sensitive business and customer information.

This repository contains the completed AWS security assessment.

## Assessment Scope

- VPC network configuration and Security Groups
- IAM users, MFA, groups, and permissions
- S3 security configuration
- CloudTrail logging and audit evidence
- External exposure validation using Nmap

## Key Findings

1. Internet-exposed SSH access
2. Missing MFA for a console-enabled IAM user
3. Excessive administrative privileges
4. S3 Block Public Access disabled
5. Customer-backup versioning disabled
6. Internet-permitted HTTP rule with no confirmed listener

## Deliverables

- Security assessment report (PDF)
- Supporting evidence screenshots
