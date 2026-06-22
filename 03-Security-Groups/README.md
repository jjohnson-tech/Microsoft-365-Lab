## 03 - Security Groups

Security groups in Microsoft 365 are used to manage access to resources by grouping users together. Instead of assigning permissions to individual users, permissions are assigned to the group — making it easy to onboard new users by simply adding them to the right group and offboard them by removing them. This section covers creating a security group and adding a member.

---

## Step 1: Navigate to Groups

Logged into the Microsoft 365 Admin Center at **admin.microsoft.com** and navigated to **Groups → Active Groups** to manage security groups for the tenant.

<img width="1892" height="700" alt="security group landing page" src="https://github.com/user-attachments/assets/fc3184e8-4063-43f8-a517-ae864ee1a750" />


---

## Step 2: Create a New Security Group

Clicked **Add a group** and selected **Security** as the group type. Security groups are used specifically for managing access to resources and permissions — they are different from Microsoft 365 Groups which are used for collaboration tools like Teams and SharePoint.

<img width="1901" height="857" alt="add security group creation page" src="https://github.com/user-attachments/assets/74db5879-7004-491d-9af6-4309f14577fc" />


---

## Step 3: Configure the Security Group Details

Filled in the group details:

- **Name:** IT Help Desk
- **Description:** Security group for IT Help Desk staff access and permissions

A clear, descriptive name and description makes it easy for other admins to understand the purpose of the group without needing additional context.

<img width="1040" height="684" alt="security group creation" src="https://github.com/user-attachments/assets/3b1eb2e6-4062-439e-b0d5-299baa8e9437" />


---

## Step 4: Confirm the Security Group Was Created

After completing the setup, confirmed the **IT Help Desk** security group appeared in the Active Groups list with the correct group type listed as Security.

<img width="1127" height="662" alt="IT Help Desk security group " src="https://github.com/user-attachments/assets/435875ad-8fa1-4067-a09b-e4ced2d279d0" />


---

## Step 5: Add a Member to the Security Group

Opened the **IT Help Desk** group and navigated to the **Members** tab. Clicked **Add members** and searched for the Test Employee account to add them to the group.

Adding users to a security group rather than assigning permissions individually is a core IT best practice — it scales cleanly as the organization grows and makes auditing access much simpler.

<img width="813" height="677" alt="added_testemployee_to_security_group" src="https://github.com/user-attachments/assets/cffcae91-5e8c-4ed3-8eee-bc77354a127e" />


---

## Summary

| Task | Action |
|---|---|
| Navigate to Groups | Opened Active Groups in the Microsoft 365 Admin Center |
| Create Security Group | Created IT Help Desk group with Security type |
| Configure Details | Set group name and description |
| Confirm Group Created | Verified group appeared in Active Groups list |
| Add Member | Added Test Employee to the IT Help Desk security group |

Security groups are fundamental to access management in Microsoft 365. Assigning permissions at the group level rather than the individual user level is the standard approach in enterprise environments and makes managing access far more efficient as organizations scale.
