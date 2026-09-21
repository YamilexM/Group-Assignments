# Microsoft Entra ID Group Assignment

## Project Overview

In this lab, I practiced managing user group membership in Microsoft Entra ID.

Building on my previous user provisioning, licensing, and role assignment labs, I reviewed Taylor Morgan's existing group memberships and then assigned the user to an IT security group.

The goal was to gain more hands-on experience with group-based identity management and understand how users can be organized into security groups within a cloud environment.

## Technologies Used

- Microsoft Entra ID
- Microsoft Azure
- Identity and Access Management (IAM)
- Security Groups

## What I Practiced

- Reviewing a user's current group memberships
- Identifying a user with no existing group memberships
- Adding a user to an existing security group
- Verifying the group membership after assignment
- Reviewing the group type, membership type, and source
- Documenting identity administration tasks

## Step 1: Review Existing Group Memberships

I opened **Taylor Morgan's** account in Microsoft Entra ID and navigated to the **Groups** section.

Before making any changes, I confirmed that the user was not currently a member of any groups.

![No Group Memberships](images/01-no-group-memberships.png)

## Step 2: Assign the User to a Security Group

I used the **Add memberships** option to assign Taylor Morgan to the existing **IT - Staff SecGroup** security group.

This allowed me to practice managing user membership within an existing Microsoft Entra security group.

## Step 3: Verify the Group Membership

After completing the assignment, I returned to Taylor Morgan's **Groups** page and confirmed that the new membership was successfully added.

The group showed:

- **Group:** IT - Staff SecGroup
- **Group Type:** Security
- **Membership Type:** Assigned
- **Source:** Cloud

![Security Group Membership Verified](images/03-security-group-membership-verified.png)

## Skills Practiced

- Microsoft Entra ID
- Identity and Access Management
- Security Group Management
- User Group Assignment
- Cloud User Administration
- Membership Verification
- Technical Documentation

## What I Learned

This lab helped me better understand how security groups can be used to organize users within Microsoft Entra ID.

I practiced reviewing a user's existing memberships, assigning the user to an appropriate security group, and verifying that the membership was successfully applied.

This also helped me see how user provisioning, licensing, role assignments, and group memberships are separate parts of managing a cloud identity.
