# Cloud-Infrastructure-Audit

An automated framework for auditing cloud environment configurations against security and operational best practices.

## Overview
This project automates the validation of cloud-native infrastructure, ensuring consistent security posture across staging and production environments. It replaces manual configuration reviews with a programmatic audit workflow.

## Key Features
- **Automated Compliance Checks:** Validates encryption, access controls, and MFA settings.
- **Infrastructure-as-Code Integration:** Designed to parse and audit configuration files before deployment.
- **Operational Efficiency:** Reduces audit cycles by automating repetitive security checks.

## Usage
1. Configure your `config.json` with the target environment parameters.
2. Execute the scanner: `python3 scanner.py`
3. Review the generated audit log for compliance scores and actionable security alerts.
