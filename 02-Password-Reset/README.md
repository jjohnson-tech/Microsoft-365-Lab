## 02 - Password Reset

Password resets are one of the most frequent helpdesk tickets in any organization. In Microsoft 365, administrators can reset user passwords directly from the Admin Center without knowing the current password. This section covers the full process of resetting a user password and forcing a change on first sign-in.

---

## Step 1: Navigate to Active Users

Logged into the Microsoft 365 Admin Center at **admin.microsoft.com** and navigated to **Users → Active Users** to locate the user account requiring a password reset.

<img width="1180" height="727" alt="active users list" src="https://github.com/user-attachments/assets/5c151841-190a-4ffb-9896-03f06c3a42b8" />


---

## Step 2: Select the User and Open Reset Password

Clicked on the **Test Employee** account to open the user details panel, then clicked **Reset password** to begin the password reset process.

<img width="1907" height="895" alt="reset password menu" src="https://github.com/user-attachments/assets/d09e572a-2b63-466a-986a-23bf3354d484" />


---

## Step 3: Configure the Password Reset Options

On the Reset password screen, configured the following options:

- **Auto-generate password** — let Microsoft 365 generate a secure temporary password
- **Require this user to change their password when they first sign in** — enabled

Auto-generating the password removes any risk of IT staff setting a password they could remember. Forcing a change on first sign-in ensures the user immediately sets their own private credentials.

<img width="1912" height="852" alt="password reset options selected" src="https://github.com/user-attachments/assets/bc5e4862-adfa-40b0-83ef-62045a64b6b6" />


---

## Step 4: Confirm Password Reset and Copy Temporary Password

After clicking **Reset password**, Microsoft 365 confirmed the reset was successful and displayed the temporary password. Copied the temporary password to share with the user through a secure communication channel.

In a real environment the temporary password would be shared with the user via a verified phone call, secure messaging platform, or in person — never via the same email account that was reset, since the user may be locked out of it.

<img width="1125" height="717" alt="password reset" src="https://github.com/user-attachments/assets/91f9381c-6eb3-4f3a-bcd1-a0fcf1db85bf" />


---

## Summary

| Step | Action |
|---|---|
| Navigate to Active Users | Located the user account in the Admin Center |
| Open Reset Password | Opened the password reset option from the user details panel |
| Configure Options | Auto-generated password with forced reset on first sign-in |
| Copy Temporary Password | Copied the temporary password to securely share with the user |

Password resets in Microsoft 365 are fast and straightforward — the key is always enabling the forced password change on first sign-in and delivering the temporary password through a secure channel, not email.
