## 04 - MFA Enablement

Multi-factor authentication (MFA) adds a second layer of security to user accounts by requiring users to verify their identity through a second method — such as a phone app or text message — in addition to their password. Enabling MFA is one of the most impactful security tasks an IT team can perform and is commonly done during onboarding or in response to security policy changes. In this lab MFA was enabled through the Microsoft Entra ID admin center.

---

## Step 1: Navigate to Microsoft Entra ID

Logged into the Microsoft 365 Admin Center at **admin.microsoft.com** and navigated to **Admin Centers → Microsoft Entra ID** to access identity and security settings for the tenant.

<img width="1907" height="866" alt="entra admin center landing page" src="https://github.com/user-attachments/assets/87bd3c31-5c29-49ed-98ca-2db5555c4afa" />


---

## Step 2: Navigate to Per-User MFA Settings

Inside Entra ID, navigated to **Users → All Users** then clicked **Per-user MFA** to access the MFA management page. Per-user MFA allows MFA to be enabled on a user-by-user basis without requiring a Conditional Access policy.

<img width="1142" height="705" alt="before enabling mfa" src="https://github.com/user-attachments/assets/a29eb23b-7dc0-4db4-8425-a25f59b5689e" />


---

## Step 3: Select the User and Enable MFA

Located the **Test Employee** account in the MFA users list and clicked **Enable** to turn on MFA for the account.

After enabling, the MFA status for the user changed from **Disabled** to **Enabled**. The user will be prompted to register their MFA method the next time they sign in.

Enabling MFA means the user must complete a second verification step every time they log in — significantly reducing the risk of unauthorized access even if their password is compromised.

<img width="1152" height="712" alt="mfa enabled for user" src="https://github.com/user-attachments/assets/3fec481d-33e6-443a-864a-46e3aa147e11" />


---

## Step 4: Confirm MFA Status

Confirmed the MFA status for the Test Employee account displayed as **Enabled** in the MFA users list, verifying the change was applied successfully.

<img width="1152" height="712" alt="mfa enabled for user" src="https://github.com/user-attachments/assets/1e21ffea-9e69-49d0-9092-f9bc7022dfac" />


---

## Summary

| Task | Action |
|---|---|
| Navigate to Entra ID | Accessed identity and security settings from the M365 Admin Center |
| Open Per-User MFA | Located the per-user MFA management page under All Users |
| Enable MFA | Enabled MFA on the Test Employee account |
| Confirm Status | Verified MFA status changed to Enabled in the users list |

MFA is one of the most effective security controls available and is a standard requirement in most enterprise environments. Enabling it per-user through Entra ID is a common helpdesk and sysadmin task — especially during onboarding or when responding to security incidents involving compromised credentials.
