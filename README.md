# Azure AD IAM Lab – Hands-on Project

## 🎯 Objective
Hands-on implementation of Identity & Access Management 
using Microsoft Azure Entra ID.

## ✅ Tasks Completed

### Task 1 – User Management
- Created 3 users in Microsoft Entra ID
- Assigned Job Title and Department to each user

### Task 2 – Group Management
- Created Security Group: IT-Team
- Added IT department users as members

### Task 3 – RBAC (Role Based Access Control)
- Assigned Reader role to testuser1
- Assigned Contributor role to testuser2
- Verified role assignments at subscription level

### Task 4 – MFA (Multi-Factor Authentication)
- Enabled MFA for testuser1
- Configured per-user MFA settings

### Task 5 – Conditional Access Policy
- Created policy: Require-MFA-All-Users
- Applied to all users and cloud apps
- Set to Report-only mode for safe testing

### Task 6 – PowerShell Automation
- Used Az PowerShell module
- Listed all Entra ID users via Get-AzADUser
- Retrieved role assignments via Get-AzRoleAssignment

## 🛠️ Tools Used
- Microsoft Azure Portal
- Microsoft Entra ID (Azure AD)
- Azure RBAC
- Conditional Access
- PowerShell (Az Module)

## 📸 Screenshots
See [/screenshots](./screenshots) folder for step-by-step proof.

## 📸 Screenshots
Users Created
<img width="1361" height="591" alt="users" src="https://github.com/user-attachments/assets/99f16156-5936-4152-a192-6fea84b887f2" />
IT-Team Security Group
<img width="1350" height="591" alt="groups" src="https://github.com/user-attachments/assets/a71537fb-5525-45c2-8dbf-be9bd447b8f0" />
RBAC (Reader + Contributor)
<img width="1358" height="593" alt="IAM" src="https://github.com/user-attachments/assets/47056bc8-b3ff-409c-ba3b-d313970ad65a" />
<img width="1140" height="516" alt="Screenshot 2026-06-15 222321" src="https://github.com/user-attachments/assets/7822e17f-46db-4591-ac55-6e21efdf9fac" />
MFA Enabled
<img width="1364" height="555" alt="MFA" src="https://github.com/user-attachments/assets/2067845f-78bd-46bb-91fa-e06ff6fb094c" />
PowerShell (Get-AzADUser + Get-AzRoleAssignment)
<img width="1366" height="768" alt="shell" src="https://github.com/user-attachments/assets/6351a3ee-b40d-4e92-98cc-878d2659dee1" />
