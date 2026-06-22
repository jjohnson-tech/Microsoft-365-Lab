 ## 01 - User Lifecycle Management

User lifecycle management covers the full process of creating a user account when someone joins the organization and properly offboarding them when they leave. In Microsoft 365 this is handled through the Admin Center and includes license assignment, account configuration, and access revocation. These are among the most common tasks performed by helpdesk and IT support teams on a daily basis.

---

## Step 1: Navigate to the Microsoft 365 Admin Center

Logged into the Microsoft 365 Admin Center at **admin.microsoft.com** using the Global Administrator account. The Admin Center is the central hub for managing all users, licenses, groups, and services across the M365 tenant.

<img width="1915" height="897" alt="m365 admin center landing page" src="https://github.com/user-attachments/assets/735a0f83-e5a7-4e58-a7db-7854379b8334" />


---

## Step 2: Create a New User Account

Navigated to **Users → Active Users → Add a user** and filled in the new user's details:

- **First Name:** Test
- **Last Name:** Employee
- **Display Name:** Test Employee
- **Username:** testemployee@jjtechlab.onmicrosoft.com
- **Password:** Auto-generated temporary password
- **Require password change at first sign-in:** Enabled

Requiring a password change at first sign-in is standard practice — it ensures the user sets their own private password immediately and prevents IT staff from knowing end-user credentials.

<img width="1422" height="775" alt="add user_creating a user" src="https://github.com/user-attachments/assets/db1d2a45-a18b-48c0-8d52-7bf60693959f" />


---

## Step 3: Assign a Microsoft 365 License

During user creation, assigned a **Microsoft 365 Business Standard** license to the new account. Assigning a license gives the user access to all included M365 applications and services — without a license the account exists but the user cannot access any M365 apps.

<img width="1422" height="775" alt="add user_creating a user" src="https://github.com/user-attachments/assets/d74ffbac-be7c-4e9e-8fd2-095c61f047dd" />


---

## Step 4: Confirm User Account Created

After completing the setup, confirmed the new user account appeared in the **Active Users** list with the correct display name, username, and license assigned.

<img width="1180" height="727" alt="active users list" src="https://github.com/user-attachments/assets/7ddae56d-cf5c-40d7-b514-041d6b0344af" />


---

## Step 5: Offboard the User — Block Sign-In

To simulate an employee departure, began the offboarding process by blocking the user's sign-in. Navigated to the user's account → **Block sign-in** and toggled it on.

Blocking sign-in immediately prevents the user from logging into any M365 service while keeping the account and all associated data intact. This is always the first step in offboarding — revoke access before taking any other action.

<img width="968" height="715" alt="account disabled" src="https://github.com/user-attachments/assets/ff992d30-0dea-4d7b-a5cb-f37191d4ba07" />


---

## Step 6: Offboard the User — Remove License

After blocking sign-in, removed the Microsoft 365 Business Standard license from the user account. Navigating to **Licenses and apps** and unchecking the license frees it up to be reassigned to another user.

Removing the license as part of offboarding is important for license management and cost control — unused licenses on inactive accounts waste money in a real organization.

<img width="917" height="705" alt="after license removal" src="https://github.com/user-attachments/assets/925d41a7-2e16-42e2-abc4-69e97b144917" />


---

## Summary

| Task | Action |
|---|---|
| Create User | Added new account with display name, username, and auto-generated password |
| Assign License | Assigned Microsoft 365 Business Standard to grant access to M365 apps |
| Force Password Reset | Enabled required password change on first sign-in |
| Block Sign-In | Immediately revoked M365 access during offboarding |
| Remove License | Freed up the license for reassignment after offboarding |

User lifecycle management in Microsoft 365 is one of the most frequent tasks helpdesk teams handle — both onboarding new hires and offboarding departing employees follow a consistent process that ensures access is granted and revoked cleanly every time.
