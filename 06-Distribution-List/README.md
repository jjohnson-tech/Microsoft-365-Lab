## 06 - Distribution List

A distribution list is a group email address that forwards incoming messages to all members of the list. When someone sends an email to the distribution list address, every member receives a copy. Distribution lists are commonly used for company-wide announcements, department communications, and team notifications. In this lab an All Staff distribution list was created and members were added to it.

---

## Step 1: Navigate to Distribution Lists

Logged into the Microsoft 365 Admin Center at **admin.microsoft.com** and navigated to **Admin Centers → Exchange** to open the Exchange Admin Center. Then navigated to **Recipients → Groups** to manage distribution lists for the tenant.

<img width="1386" height="410" alt="group email add landing page" src="https://github.com/user-attachments/assets/3f58c284-cc25-40e3-b0ce-b9412b05da97" />


---

## Step 2: Create a New Distribution List

Clicked **Add a group** and selected **Distribution list** as the group type. Distribution lists are specifically designed for group email — they are different from security groups which are used for access control and permissions.

<img width="1912" height="852" alt="distro group selected" src="https://github.com/user-attachments/assets/ffb7274c-57cc-4af7-b404-b63dabc5125b" />


---

## Step 3: Configure the Distribution List Details

Filled in the distribution list details:

- **Name:** All Staff
- **Email address:** allstaff@jjtechlab.onmicrosoft.com
- **Description:** Company-wide distribution list for all staff announcements

A clear name and email address makes it easy for anyone in the organization to know who they are emailing when they send to the list.

<img width="1917" height="861" alt="distro group add details" src="https://github.com/user-attachments/assets/1dd0be79-9478-429d-aa66-e6c532d3ca40" />


---

## Step 4: Add Members to the Distribution List

After the distribution list was created, opened the **All Staff** group and navigated to the **Members** tab. Clicked **Add members** and added the Test Employee account to the list.

Every user added to the distribution list will receive a copy of any email sent to allstaff@jjtechlab.onmicrosoft.com. In a real environment all employees would be added to an All Staff list so company-wide communications reach everyone automatically.

<img width="1902" height="856" alt="added test employee to distro" src="https://github.com/user-attachments/assets/b3f8be34-3a5b-4df7-880a-5870ccfee3c2" />


---

## Step 5: Confirm the Distribution List and Members

Confirmed the **All Staff** distribution list appeared in the Groups list with the correct email address and that the Test Employee account was listed as a member.

<img width="1897" height="832" alt="member and group list confirm for distro" src="https://github.com/user-attachments/assets/928700ce-454c-4bc9-b14b-83791d90ae24" />


---

## Summary

| Task | Action |
|---|---|
| Navigate to Groups | Opened Recipients → Groups in the Exchange Admin Center |
| Create Distribution List | Created All Staff list with allstaff@jjtechlab.onmicrosoft.com |
| Configure Details | Set name, email address, and description |
| Add Members | Added Test Employee to receive all staff emails |
| Confirm | Verified list and membership in the Groups page |

Distribution lists are a core part of email management in Microsoft 365. They allow organizations to communicate with entire departments or the whole company through a single email address without needing to manually add recipients every time. Creating and managing distribution lists is a common task for M365 administrators and helpdesk teams.
