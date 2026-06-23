## 05 - Shared Mailbox

A shared mailbox allows multiple users to send and receive email from a single shared email address without requiring a dedicated Microsoft 365 license. Shared mailboxes are commonly used for team inboxes like helpdesk@company.com or support@company.com where multiple staff members need to monitor and respond to incoming requests. In this lab a Help Desk shared mailbox was created and a user was given access to it.

---

## Step 1: Navigate to Shared Mailboxes

Logged into the Microsoft 365 Admin Center at **admin.microsoft.com** and navigated to **Admin Centers → Exchange** to open the Exchange Admin Center, then navigated to **Recipients → Mailboxes** and filtered by Shared to manage shared mailboxes for the tenant.

<img width="1912" height="867" alt="shared mailbox landing page" src="https://github.com/user-attachments/assets/8cbad226-3a6d-4836-a7f8-d9f5c249d2a4" />


---

## Step 2: Create a New Shared Mailbox

Clicked **Add a shared mailbox** and filled in the mailbox details:

- **Name:** HelpDesk
- **Email address:** helpdesk@jjtechlab.onmicrosoft.com

The display name is what recipients see when they receive an email from the shared mailbox. The email address is what users will send to when contacting the Help Desk team.

<img width="1917" height="887" alt="help desk add mailbox" src="https://github.com/user-attachments/assets/418917c7-7c27-4a7f-93ce-69da1cadc8d0" />



---

## Step 3: Confirm the Shared Mailbox Was Created

After completing the setup, confirmed the **Help Desk** shared mailbox appeared in the shared mailboxes list with the correct email address assigned.

<img width="1900" height="857" alt="helpdesk confirmation" src="https://github.com/user-attachments/assets/ed1c1f9a-594c-4029-aa8a-96108c79f118" />



---

## Step 4: Add a Member to the Shared Mailbox

Opened the **Help Desk** shared mailbox and navigated to **Members** to add users who need access to send and receive from the shared inbox. Clicked **Add members** and added the Test Employee account.

Once added as a member, the user can access the Help Desk inbox directly from their own Outlook account and send emails as helpdesk@jjtechlab.onmicrosoft.com.

<img width="1901" height="846" alt="add member to help desk email" src="https://github.com/user-attachments/assets/f1334257-780b-47e9-9195-96ce30cf1303" />

<img width="1917" height="862" alt="confirmation of member added" src="https://github.com/user-attachments/assets/7f2aa3e8-62a3-4309-b09a-9f4cabfa33eb" />


---

## Summary

| Task | Action |
|---|---|
| Navigate to Shared Mailboxes | Opened shared mailbox management in the Admin Center |
| Create Shared Mailbox | Created HelpDesk mailbox with helpdesk@jjtechlab.onmicrosoft.com |
| Confirm Creation | Verified mailbox appeared in the shared mailboxes list |
| Add Member | Added Test Employee to grant access to the shared inbox |

Shared mailboxes are a cost-effective way to manage team email in Microsoft 365 — they don't require a dedicated license and allow multiple staff members to collaborate on incoming requests from a single address. Creating and managing shared mailboxes is a common task for helpdesk and M365 administrators.
