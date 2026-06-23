## 07 - Teams Provisioning

Microsoft Teams is the primary collaboration platform in Microsoft 365, used for chat, video calls, file sharing, and team workspaces. Provisioning a Teams workspace involves creating a new team, configuring its privacy settings, and adding the right members and owners. In this lab a private IT Help Desk Teams workspace was created to simulate how IT departments set up dedicated collaboration spaces for their team.

---

## Step 1: Navigate to the Teams Admin Center

Logged into the Microsoft 365 Admin Center at **admin.microsoft.com** and navigated to **Admin Centers → Teams** to open the Microsoft Teams Admin Center at **admin.teams.microsoft.com**.

The Teams Admin Center is where administrators manage all Teams settings, policies, and workspaces across the organization.

<img width="1917" height="822" alt="teams landing page" src="https://github.com/user-attachments/assets/aeff5ec5-7c60-4f4b-8ddb-3d5f25bddb48" />


---

## Step 2: Navigate to Manage Teams

Inside the Teams Admin Center, navigated to **Teams → Manage Teams** to view all existing teams in the tenant and access the option to create a new one.

<img width="1902" height="670" alt="managing teams creating landing page" src="https://github.com/user-attachments/assets/a8344f02-a58d-4d9c-9277-f47449c600f2" />


---

## Step 3: Create a New Team

Clicked **Add** to begin creating a new Teams workspace. Filled in the team details:

- **Name:** IT Help Desk
- **Description:** Private workspace for IT Help Desk staff — used for internal communication, ticket tracking, and team collaboration
- **Privacy:** Private — only owners can add members and the team is not visible to everyone in the organization

A private team is the appropriate setting for an IT Help Desk workspace since access should be restricted to authorized IT staff only.

<img width="622" height="875" alt="teams it help desk details" src="https://github.com/user-attachments/assets/9bc790a9-fe69-451c-80a0-14a8dd8f3021" />


---

## Step 4: Add Members and Assign Ownership

After the team was created, opened the **IT Help Desk** team and navigated to the **Members** tab. Added the Test Employee account as a member and confirmed the Global Administrator was set as the team owner.

Team owners can add and remove members, create and delete channels, and manage team settings. Members can participate in channels but have limited administrative control.

<img width="1905" height="857" alt="teams it help desk showing members" src="https://github.com/user-attachments/assets/436d8cc6-fdf5-4987-86c1-9d569e415fdb" />


---

## Step 5: Confirm the Team Was Created

Confirmed the **IT Help Desk** team appeared in the Manage Teams list with the correct privacy setting of Private and the correct number of members.

<img width="1912" height="807" alt="managed teams confirmation" src="https://github.com/user-attachments/assets/1d51eaff-778b-4aa4-bc29-77616b2cc881" />


---

## Summary

| Task | Action |
|---|---|
| Navigate to Teams Admin Center | Opened Teams Admin Center from the M365 Admin Center |
| Navigate to Manage Teams | Located the Teams management page |
| Create Team | Added IT Help Desk team with Private privacy setting |
| Add Members | Added Test Employee as member and confirmed Global Admin as owner |
| Confirm | Verified IT Help Desk team appeared in Manage Teams list |

Provisioning Teams workspaces through the Teams Admin Center is the standard approach for IT administrators. Setting the correct privacy level, assigning ownership, and adding the right members during setup ensures the workspace is secure and properly managed from day one.
