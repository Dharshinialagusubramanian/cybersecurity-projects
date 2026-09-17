# Windows IAM & Access Control Lab

## Cybersecurity Project 01

### Objective

The objective of this project is to understand the fundamentals of Identity and Access Management (IAM) and Windows access control by creating a local user, assigning the user to a group, configuring permissions, and verifying authorized file access.

### Concepts Learned

- Identity and Access Management (IAM)
- Authentication
- Authorization
- Users and Groups
- Permissions
- Least Privilege
- Access Control Lists (ACLs)

### Tools Used

- Windows 11 Home
- Command Prompt (Administrator)
- Windows Settings
- net user
- net localgroup
- icacls
- runas

### Practical Implementation

#### 1. Create Local User

Created a local Windows user account named `Gowtham` using Windows Settings.

#### 2. Create Security Group

Created a local security group named `Developers`.

```text
net localgroup Developers /add
