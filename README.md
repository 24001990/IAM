# EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team

## NAME: Dodla Susmitha
## REG. NO: 212224110016
---

## Aim

To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

---

## Algorithm

1. Sign in to the AWS Management Console.
2. Navigate to the IAM service.
3. Create IAM groups with defined policies (e.g., Admin, Developer).
4. Create IAM users and assign them to appropriate groups.
5. Create IAM roles if cross-account or service-based access is needed.
6. Attach permissions using managed or custom policies.
7. Enable MFA (Multi-Factor Authentication) for users.
8. Monitor access using IAM Access Analyzer and CloudTrail.

---

## Procedure

### 1. Access IAM

- Go to *AWS Console* → *Services* → *IAM*.

### 2. Create IAM Groups

- Click *Groups* → *Create New Group*.
- Name the group (e.g., Admins, Developers).
- Attach predefined or custom policies (e.g., AmazonEC2FullAccess).

### 3. Create IAM Users

- Click *Users* → *Add Users*.
- Enter usernames and choose *Programmatic access* and/or *AWS Management Console access*.
- Assign users to the appropriate group.

### 4. Create IAM Roles (if needed)

- Go to *Roles* → *Create Role*.
- Select use case (AWS service, another AWS account).
- Attach necessary permissions.

### 5. Apply Policies

- Use AWS managed policies or create custom JSON-based policies.
- Assign them to users, groups, or roles.

### 6. Enable MFA

- For each user, go to *Security credentials*.
- Click *Manage MFA* → Choose *Virtual MFA device* (e.g., Google Authenticator).

### 7. Monitor IAM Usage

- Use *IAM Access Analyzer* to detect unused permissions.
- Use *CloudTrail* for auditing user activity.

---

### Outcome

## 1.IAM Group Creation

<img width="1600" height="738" alt="WhatsApp Image 2026-09-12 at 4 01 50 PM" src="https://github.com/user-attachments/assets/5a63cf19-c0b8-4996-9850-3da51d949b2c" />

## 2.Attach an IAM Policy to the group

<img width="1237" height="555" alt="WhatsApp Image 2026-09-12 at 4 06 09 PM" src="https://github.com/user-attachments/assets/5e7bd31b-baa2-4741-99a7-6301e36280d2" />

## 3.Create an IAM User

<img width="1047" height="571" alt="WhatsApp Image 2026-09-12 at 4 25 20 PM" src="https://github.com/user-attachments/assets/2f09a65c-c8c1-45e9-877a-321b7044123a" />



## 4.Add The user to the IAM Group

<img width="1252" height="590" alt="WhatsApp Image 2026-09-12 at 4 10 48 PM" src="https://github.com/user-attachments/assets/f963ea0e-e9ad-4e96-a179-cd9ae67eca44" />


## 5.Verify user Permissions

<img width="1252" height="615" alt="WhatsApp Image 2026-09-12 at 4 20 25 PM" src="https://github.com/user-attachments/assets/9392a40c-fa22-48f4-8767-77cc2cc3fd8c" />


## 6.Verify Least-Privilege Access

<img width="1232" height="552" alt="WhatsApp Image 2026-09-12 at 4 15 24 PM" src="https://github.com/user-attachments/assets/76c0e067-f207-456f-840d-dbedb38d4b9a" />


<img width="1272" height="647" alt="WhatsApp Image 2026-09-12 at 4 17 05 PM" src="https://github.com/user-attachments/assets/33a4bcee-b0ee-43b2-9339-7ccb8dd75b77" />





---

## Result

Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
