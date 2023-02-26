# Week 0 — Billing and Architecture

## Assignment

1. Established a new account on Lucid Charts and developed a logical architectural diagram.
2. Implemented multi-factor authentication (MFA) for the root user account.
3. Set up an IAM user account within the 'Admin' user group.
4. Granted the IAM user 'Role Access to Billing Information.'
5. Generated AWS credentials, specifically an Access Key, for usage.
6. Installed the most recent edition of AWS CLI, using the gitpod workspace.
7. Configured an AWS Budget with the help of AWS CLI commands.
8. Installed BFG Repo Cleaner, a software tool.
9. Established new accounts for the Gitpod, Momento, and Honeycomb applications.


### 1: Recreating the logical drawing

I was able to create an account in Lucid Charts and recreate the Logical drawing in for the cruddur app.
<https://lucid.app/lucidchart/f3c66b9e-f034-4535-bc86-4c0bdbf8dd9f/edit?viewport_loc=-639%2C12%2C3076%2C1471%2C0_0&invitationId=inv_b75b2088-4eeb-469a-b0cf-ea872426952b>

### 2: Implement MFA in Root user.
I enabled the MFA of my root user as shown.
/assets/AWS 2FA

### 3 and 4: Set up an IAM user account 

As a security measure to reduce the exposure of the root user, I have created a new user in AWS IAM. However, I have granted excessive permissions to the user by assigning the AdministratorAccess policy, which allows the user to access all AWS resources and services. The user will use an Access key to access these resources.

/assets/created admin user

## 5: Generated AWS credentials, specifically an Access Key

I generated access keys from my IAM user so as to secure my account and give specific access to the account and the key.

### 6: Installing AWS CLI

I used VS Code to install the AWS CLI extention as shown below.
/assets/installing aws cli

### 7: Configure Budget and billing alarms
Created Monthly Cost Budget

