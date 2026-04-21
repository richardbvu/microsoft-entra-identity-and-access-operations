# Microsoft Entra Identity And Access Operations Lab

## Overview
This project demonstrates the build, validation, and troubleshooting of a Microsoft Entra environment focused on identity, access, authentication, and policy operations.

It covers core Entra administration tasks such as tenant validation, cloud user management, role assignment, sign-in and audit log review, group and membership management, and scoped administration, along with deeper hands-on work in Conditional Access, MFA and authentication methods, authentication strengths, self-service password reset, Temporary Access Pass recovery, and dynamic user and device groups.

The lab reflects common IT support and identity administration scenarios, including reviewing sign-in behavior, validating Conditional Access scope, troubleshooting MFA method mismatches, testing self-service recovery workflows, recovering user access with Temporary Access Pass, and validating dynamic targeting based on user and device attributes.

All configurations and findings were validated through portal-based management, controlled break/fix testing, user-side validation, and documented troubleshooting evidence. The project follows an evidence-first approach, with build validation, troubleshooting scenarios, ticket write-ups, runbooks, and interview-ready documentation aligned to real IT support and identity operations workflows.

## Work Performed
- Validated the Microsoft Entra tenant and reviewed baseline identity configuration  
- Managed cloud-only user lifecycle actions, including profile updates, blocked sign-in, password reset, deletion, and restore workflows  
- Assigned and validated administrative roles to demonstrate least-privilege access concepts  
- Reviewed sign-in logs, audit logs, and scoped administration behavior in Microsoft Entra  
- Built and tested Conditional Access policies using report-only mode, What If validation, and enforced MFA scenarios  
- Troubleshot Conditional Access scope issues, report-only evaluation behavior, and sign-in log interpretation  
- Reviewed authentication methods policy and validated Microsoft Authenticator, Software OATH token, and authentication strength behavior  
- Tested self-service password reset registration and pilot scoping using a selected SSPR group  
- Used Temporary Access Pass to support recovery and authentication method registration through Security info  
- Created and validated dynamic user and device groups using attribute-based membership rules  
- Troubleshot dynamic group targeting failures caused by inconsistent user attribute values  
- Built troubleshooting evidence, ticket write-ups, runbooks, and interview stories from real break/fix scenarios  

## Start Here
Recommended files and folders to review first:

- [04-Ticket-Pack](./04-Ticket-Pack/)
- [03-Runbook](./03-Runbook/)
- [06-Resume-and-Interview](./06-Resume-and-Interview/)

## Skills Demonstrated
- Microsoft Entra tenant administration  
- Cloud-only user lifecycle management  
- Microsoft Entra role assignment and least-privilege administration  
- Sign-in log and audit log review  
- Conditional Access policy design, validation, and troubleshooting  
- MFA enforcement, authentication methods, and authentication strength analysis  
- Software OATH token and Authenticator-based sign-in validation  
- Self-service password reset configuration and registration workflow review  
- Temporary Access Pass recovery and onboarding support  
- Dynamic user and device group creation and troubleshooting  
- Attribute-based access targeting and membership validation  
- Structured troubleshooting methodology and documentation  

## Project Structure
- [00-Project-Summary](./00-Project-Summary/) — overview and navigation  
- [01-Build-Evidence](./01-Build-Evidence/) — healthy-state build validation  
- [02-Troubleshooting-Evidence](./02-Troubleshooting-Evidence/) — raw notes, screenshots, and observations  
- [03-Runbook](./03-Runbook/) — reusable troubleshooting procedures  
- [04-Ticket-Pack](./04-Ticket-Pack/) — polished ticket write-ups  
- [06-Resume-and-Interview](./06-Resume-and-Interview/) — project packaging for job search  