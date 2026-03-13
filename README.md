# aws-iam-user-creation

# AWS IAM User Creation Project

## Project Overview

This project explains the **step-by-step process of creating an IAM user in AWS** using the AWS Management Console.

AWS IAM (Identity and Access Management) allows administrators to securely manage access to AWS services and resources by creating users and assigning permissions.

---

## Prerequisites

Before starting the IAM user creation process, ensure the following:

- AWS Account
- Access to AWS Management Console
- Basic understanding of AWS services
- Administrative permissions to create IAM users

---

## Steps to Create an IAM User

### Step 1: Login to AWS Console

1. Open the AWS Management Console.
2. Enter your credentials.
3. Click **Sign In**.

---

### Step 2: Navigate to IAM Service

1. In the AWS services search bar, type **IAM**.
2. Select **IAM (Identity and Access Management)**.
3. IAM dashboard will open.

---

### Step 3: Open Users Section

1. In the left navigation panel, click **Users**.
2. Click **Create user**.

---

### Step 4: Enter User Details

1. Enter the **User name**.
2. Select the type of access required.

Example username:

```
devops-user
```

---

### Step 5: Set Permissions

Choose how to assign permissions to the user.

Options include:

- Add user to group
- Copy permissions from existing user
- Attach policies directly

Example policy:

```
AdministratorAccess
```

---

### Step 6: Review Configuration

1. Review user details.
2. Verify permissions and access type.

---

### Step 7: Create User

Click **Create user** to complete the process.

---

## IAM Concepts

### IAM User
An IAM user represents a person or application that interacts with AWS services.

### IAM Group
A collection of IAM users that share the same permissions.

### IAM Policy
A document that defines permissions for actions on AWS resources.

---

## Benefits of Using IAM

- Secure access management
- Role-based access control
- Multi-user account management
- Improved security for AWS resources

---

## Example Use Case

An organization creates IAM users for different teams such as:

- Developers
- DevOps Engineers
- Database Administrators
- Security Team

Each team is assigned specific permissions based on their responsibilities.

---

## Conclusion

AWS IAM helps organizations securely manage access to AWS services by creating users, groups, and policies. Proper IAM configuration ensures better security and controlled access to cloud resources.

---

## Author

Poonam Langote

---

## Project Status

Completed
