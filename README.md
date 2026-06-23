# Microsoft-365-Lab
Hands-on Microsoft 365 lab covering admin center administration and end-user application support including user lifecycle management, MFA, shared mailboxes, SharePoint, and Teams.

## Overview
Using a Microsoft 365 Business trial tenant, this lab covers two areas of M365 — admin center administration and end-user application support. The admin center portion simulates common IT tasks performed by helpdesk and sysadmin teams including user lifecycle management, security groups, MFA, shared mailboxes, distribution lists, and Teams provisioning. The applications portion covers end-user facing tasks that helpdesk staff are frequently asked to support including Outlook configuration, SharePoint site management, and Microsoft Teams channel administration.

---

## Technologies Used
- Microsoft 365 Business Trial Tenant
- Microsoft 365 Admin Center
- Microsoft Entra ID (Azure AD)
- Microsoft Outlook
- Microsoft SharePoint
- Microsoft Teams
- Exchange Online

---

## Lab Environment

| Resource | Details |
|---|---|
| Tenant | jjtechlab.onmicrosoft.com |
| Admin Account | Global Administrator |
| Test User | Test Employee (testemployee@jjtechlab.onmicrosoft.com) |
| License | Microsoft 365 Business Standard |

---

## What I Built

### Part 1 — M365 Admin Center

**User Lifecycle Management** — Created a new user account, assigned a Microsoft 365 Business Standard license, and configured a temporary password with forced reset on first login. Performed offboarding by removing the license and blocking sign-in to revoke access immediately while preserving account data.

**Password Reset** — Reset a user password and configured an auto-generated temporary password with forced reset on first sign-in, simulating a standard helpdesk access request ticket.

**Security Groups** — Created an IT Help Desk security group to simulate role-based access control and added a user as a member to demonstrate group-based permission management.

**MFA Enablement** — Enabled multi-factor authentication for a user account via the Entra ID admin center, simulating a common security task performed during onboarding or in response to account security tickets.

**Shared Mailbox** — Created a Help Desk shared mailbox allowing multiple IT staff to send and receive email from a single shared address without requiring a dedicated user license.

**Distribution List** — Created an All Staff distribution list and added members to simulate company-wide email communication management.

**Teams Provisioning** — Created a private Microsoft Teams workspace for the IT Help Desk team, configured ownership and membership, and set access to Private to restrict it to authorized IT staff only.

### Part 2 — M365 Applications

**Outlook Auto Reply** — Configured an automatic reply with a custom out of office message and defined start and end time, simulating a common helpdesk request to assist users with email auto-reply setup during planned absences.

**Outlook Mail Rules** — Created a mail rule to automatically route emails from a specific sender to a designated folder, simulating a helpdesk request to help users organize and manage their inbox.

**SharePoint Team Site** — Created a private SharePoint team site using the IT Help Desk template to provision a collaborative workspace for IT staff with restricted access controls.

**SharePoint Document Library** — Created a Help Desk Resources folder inside the SharePoint document library to organize IT resources and simulate file management tasks performed when provisioning team workspaces.

**Teams Channel Management** — Created a Standard channel inside the IT Help Desk Teams workspace for tracking escalated tickets, demonstrating Teams administration and channel management skills.

---

## Table of Contents

### Part 1 — M365 Admin Center

| # | Section | Description |
|---|---|---|
| 01 | [User Lifecycle Management](01-user-lifecycle-management/README.md) | Created and offboarded a user — license assignment, sign-in block, and account deactivation |
| 02 | [Password Reset](02-password-reset/README.md) | Reset a user password with forced change on first sign-in |
| 03 | [Security Groups](03-security-groups/README.md) | Created an IT Help Desk security group and added a user as a member |
| 04 | [MFA Enablement](mfa-enablement/README.md) | Enabled multi-factor authentication for a user via Entra ID |
| 05 | [Shared Mailbox](05-shared-mailbox/README.md) | Created a Help Desk shared mailbox for the IT team |
| 06 | [Distribution List](06-distribution-list/README.md) | Created an All Staff distribution list and added members |
| 07 | [Teams Provisioning](07-teams-provisioning/README.md) | Provisioned a private IT Help Desk Teams workspace |

### Part 2 — M365 Applications

| # | Section | Description |
|---|---|---|
| 08 | [Outlook Auto Reply](08-outlook-auto-reply/README.md) | Configured automatic reply with custom message and scheduled time range |
| 09 | [Outlook Mail Rules](09-outlook-mail-rules/README.md) | Created a mail rule to auto-route emails to a designated folder |
| 10 | [SharePoint Team Site](10-sharepoint-team-site/README.md) | Created a private IT Help Desk SharePoint team site |
| 11 | [SharePoint Document Library](11-sharepoint-document-library/README.md) | Created a Help Desk Resources folder in the document library |
| 12 | [Teams Channel Management](12-teams-channel-management/README.md) | Created a Ticket Escalations channel in the IT Help Desk Teams workspace |

---

## Key Takeaways
- Managed the full M365 user lifecycle from onboarding to offboarding through the Admin Center
- Configured security controls including MFA and role-based group access
- Provisioned shared communication resources including shared mailboxes, distribution lists, and Teams workspaces
- Supported end-user facing M365 applications covering Outlook, SharePoint, and Teams
- Practiced the tasks most commonly handled by helpdesk and junior sysadmin teams in Microsoft 365 environments
