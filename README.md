# Microsoft 365 and IAM Lab 2026

## Overview

This repository documents the creation and configuration of a hands-on Microsoft 365 Identity and Access Management (IAM) lab environment.

The lab was built using a personal Windows laptop upgraded to Windows Pro and enrolled into a Microsoft 365 tenant for testing identity, authentication, device management, and access control scenarios.

The purpose of this project was to gain practical experience with Microsoft cloud technologies and develop skills relevant to Identity and Access Management (IAM), Microsoft 365 Administration, and Cloud Security roles.

---

## Project Objectives

The primary goals of this lab were to:

- Learn Microsoft Entra ID administration
- Configure and test Microsoft Intune
- Implement Multi-Factor Authentication (MFA)
- Create and manage Conditional Access policies
- Join a Windows device to Microsoft Entra ID
- Enroll a Windows device into Microsoft Intune
- Explore Zero Trust security concepts
- Document troubleshooting and implementation processes

---

## Lab Environment

### Hardware

- Personal Windows laptop

### Operating System

- Windows Pro

### Cloud Services

- Microsoft Entra ID
- Microsoft Intune
- Microsoft 365 Admin Center

### Security Technologies

- Multi-Factor Authentication (MFA)
- Conditional Access
- Device Compliance
- Modern Authentication

---

## Lab Architecture

```text
+-----------------------+
| Personal Windows Pro  |
| Device                |
+-----------+-----------+
            |
            |
            v
+-----------------------+
| Microsoft Entra ID    |
| Identity Provider     |
+-----------+-----------+
            |
            |
            v
+-----------------------+
| Conditional Access    |
+-----------+-----------+
            |
            |
            v
+-----------------------+
| Multi-Factor Auth     |
+-----------+-----------+
            |
            |
            v
+-----------------------+
| Microsoft Intune      |
| Device Management     |
+-----------------------+
```

---

## Technologies Used

### Microsoft Entra ID

- User Management
- Group Administration
- Device Registration
- Microsoft Entra Join
- Administrative Role Assignments

### Microsoft Intune

- Device Enrollment
- Device Management
- Device Compliance
- Endpoint Administration

### Microsoft 365

- Tenant Administration
- Identity Management
- Security Configuration

### Security Controls

- Multi-Factor Authentication
- Conditional Access Policies
- Legacy Authentication Blocking
- Zero Trust Principles

---

## Implemented Configurations

### Microsoft Entra ID

Configured and tested:

- User account management
- Administrative roles
- Device registration
- Device join status
- Authentication methods

---

### Microsoft Intune

Configured and tested:

- Windows device enrollment
- Device management
- Inventory visibility
- Device compliance review

---

### Conditional Access

Implemented baseline Conditional Access policies.

#### Require MFA for All Users

Purpose:

- Increase account security
- Reduce risk from compromised credentials

#### Require MFA for Administrative Roles

Purpose:

- Protect privileged accounts
- Strengthen administrative access controls

#### Block Legacy Authentication

Purpose:

- Prevent basic authentication usage
- Encourage modern authentication protocols

---

### Multi-Factor Authentication

Configured MFA for:

- Standard user accounts
- Administrative accounts

Tested:

- Authentication prompts
- Policy enforcement
- Sign-in validation

---

## Device Enrollment Process

The personal Windows Pro laptop was:

1. Prepared for enrollment
2. Connected to Microsoft Entra ID
3. Registered within the Microsoft 365 tenant
4. Enrolled into Microsoft Intune
5. Verified as a managed device

This provided hands-on experience with the device lifecycle from registration through management.

---

## Challenges and Troubleshooting

Several challenges were encountered during the lab process.

### Troubleshooting Areas

- Windows edition requirements
- Device enrollment configuration
- Microsoft Entra ID join process
- Intune enrollment behavior
- Conditional Access testing
- MFA registration and validation

### Key Takeaways

- Proper Windows editions are important for enterprise features.
- Entra ID and Intune integrations require careful configuration.
- Conditional Access policies should be tested before broad deployment.
- Documentation significantly improves troubleshooting efficiency.
- Hands-on experience provides much deeper understanding than theoretical study alone.

---

## Screenshots

Repository screenshots demonstrate:

### Microsoft Entra ID

- User administration
- Groups
- Device registration
- Administrative roles

### Microsoft Intune

- Managed devices
- Enrollment status
- Device compliance

### Conditional Access

- MFA policies
- Administrative protections
- Legacy authentication blocking

### Microsoft 365 Administration

- Tenant configuration
- Identity management settings

### Troubleshooting

- Configuration changes
- Enrollment verification
- Policy validation

---

## Skills Demonstrated

### Identity and Access Management

- Microsoft Entra ID Administration
- User Lifecycle Management
- Group Management
- Role-Based Access Control (RBAC)

### Device Management

- Microsoft Intune Administration
- Device Enrollment
- Device Compliance Monitoring

### Security Administration

- Conditional Access
- MFA Implementation
- Access Control
- Identity Security Best Practices

### Troubleshooting

- Root Cause Analysis
- Issue Investigation
- Configuration Validation
- Technical Documentation

---

## Repository Structure

```text
Microsoft-365-IAM-Lab-2026
│
├── README.md
│
├── docs
│   ├── Lab-Overview.md
│   ├── Entra-ID-Configuration.md
│   ├── Intune-Enrollment.md
│   ├── Conditional-Access.md
│   ├── MFA-Implementation.md
│   ├── Troubleshooting.md
│   └── Lessons-Learned.md
│
├── screenshots
│   ├── EntraID
│   ├── Intune
│   ├── ConditionalAccess
│   ├── MFA
│   └── Troubleshooting
│
└── diagrams
    └── Lab-Architecture.png
```

---

## Lessons Learned

This lab reinforced several important concepts:

- Identity is the new security perimeter.
- MFA remains one of the most effective security controls.
- Device trust and compliance are important components of Zero Trust.
- Conditional Access policies provide powerful access control capabilities.
- Successful IAM administration requires both technical knowledge and troubleshooting skills.

---

## Future Enhancements

Future additions planned for this lab include:

- Microsoft Defender for Endpoint
- Privileged Identity Management (PIM)
- Identity Protection
- Access Reviews
- Administrative Units
- Dynamic Groups
- Microsoft Sentinel integration
- KQL investigations

---

## Related Projects

Additional IAM and security exercises can be found in my companion IAM repository.

---

## Author

**Michelle**

IAM Support Technician

Focused on developing hands-on experience in:

- Microsoft Entra ID
- Microsoft Intune
- Microsoft 365 Administration
- Identity and Access Management
- Cloud Security
- Zero Trust Architecture

---

## License

This project is licensed under the MIT License.
