## 09 - Outlook Mail Rules

Mail rules in Outlook automatically take action on incoming emails that match specific conditions — such as moving emails from a certain sender to a designated folder, marking them as read, or flagging them for follow-up. This saves time and keeps the inbox organized without manual sorting. In this lab a mail rule was created to automatically route emails from a specific sender to a designated folder. These steps reflect the current new Outlook interface.

---

## Step 1: Open Outlook and Locate an Email

Logged into Microsoft Outlook at **outlook.office.com** using the **javierjohnson@jjtechlab.onmicrosoft.com** account. Located an existing email in the inbox from the sender the rule will be built around.

<img width="1897" height="845" alt="outlook email " src="https://github.com/user-attachments/assets/8c7beef9-b9c6-46a2-a615-754e1997bc3f" />


---

## Step 2: Right-Click the Email and Select Advanced Actions → Create Rule

Right-clicked on the email to open the context menu. In the new Outlook, navigated to **Advanced actions → Create rule** to begin building a new mail rule based on that email.

The new Outlook automatically pre-fills the sender's email address as the rule condition — making it fast to set up the most common type of rule without needing to configure it manually.

<img width="1891" height="845" alt="outlook create rule starter" src="https://github.com/user-attachments/assets/2d12cae2-604a-47cd-9003-f50ae363c4b6" />


---

## Step 3: Select a Folder or Click More Options

After clicking **Create rule**, Outlook prompted to either:
- **Select a folder** from the dropdown to immediately create a simple move rule, or
- Click **More options** to access the full rule configuration screen

Clicked **More options** to access all available conditions and actions for a more customized rule.

<img width="1847" height="842" alt="outlook more rules" src="https://github.com/user-attachments/assets/6759228b-e6d5-4e9d-8bff-ab48d59fcab3" />


---

## Step 4: Name the Rule

In the full rule settings screen, gave the rule a clear and specific name:

- **Rule name:** Move IT Help Desk Emails to IT Folder

Giving rules descriptive names makes them easy to identify and manage later — especially when multiple rules are active.

<img width="1865" height="817" alt="outlook name rule" src="https://github.com/user-attachments/assets/5e0c0bb4-f9a5-494f-a23c-48dd650ef431" />


---

## Step 5: Set the Rule Condition

Under the conditions section, confirmed the rule was set to trigger when an email is received **from a specific sender**:

- **Condition:** From — helpdesk@jjtechlab.onmicrosoft.com

Additional conditions can be added by clicking **Add another condition** if needed.

<img width="1837" height="841" alt="outlook condition" src="https://github.com/user-attachments/assets/c38460d1-4abd-4bb5-96a1-7727a0d71db1" />


---

## Step 6: Set the Rule Action

Under the actions section, configured the rule to automatically **move the email to a specific folder** when the condition is met:

- **Action:** Move to folder — IT Help Desk

If the destination folder did not already exist, created it first by clicking **New folder** in the folder picker.

<img width="1817" height="896" alt="set rule action" src="https://github.com/user-attachments/assets/cd3b1a8a-b7d1-4a33-bd4a-d57d86b7bbc7" />


---

## Step 7: Save the Rule and Run Now

Clicked **Save** to apply the rule. Enabled **Run rule now** to immediately apply the rule to any existing emails in the inbox that already match the condition.

<img width="1772" height="812" alt="outlook rule settings" src="https://github.com/user-attachments/assets/b4940223-1657-40f4-b1a7-3a41d63b3fd4" />



---

## Step 8: Verify the Rule in Settings → Mail → Rules

To confirm the rule was saved correctly, navigated to **Settings → Mail → Rules** to open the rules management page. Confirmed the **Move IT Help Desk Emails to IT Folder** rule appeared in the list and was toggled on.

From this page rules can also be reordered, edited, paused, or deleted at any time.

<img width="1735" height="811" alt="outlook rule saved" src="https://github.com/user-attachments/assets/0d1289d9-392a-48ec-9f2d-70146ceb425c" />


---

## Summary

| Task | Action |
|---|---|
| Locate Email | Found an email from the target sender in the inbox |
| Right-Click and Create Rule | Used Advanced actions → Create rule from the context menu |
| Access Full Settings | Clicked More options to configure conditions and actions |
| Name the Rule | Gave the rule a clear descriptive name |
| Set Condition | Configured rule to trigger on emails from a specific sender |
| Set Action | Configured rule to move matching emails to the IT Help Desk folder |
| Save and Run | Saved the rule and ran it on existing inbox emails immediately |
| Verify Rule | Confirmed rule appeared and was active in Settings → Mail → Rules |

In the new Outlook, rules are created via right-click → **Advanced actions → Create rule** and managed in **Settings → Mail → Rules**. Knowing this updated path is important for helpdesk staff assisting users who are used to the old interface.
