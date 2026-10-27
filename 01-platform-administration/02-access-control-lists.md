
# Lab 02: Manage Data Access Control (ACLs)

## Overview

This lab demonstrates my hands-on experience configuring and testing Access Control Lists (ACLs) within the ServiceNow platform as part of the ServiceNow RiseUp program.

The exercise focused on implementing role-based access restrictions, managing table- and field-level permissions, testing user access, and troubleshooting security rules.

## Objectives

- Understand how ACLs control access to ServiceNow data
- Create and configure Access Control Rules
- Configure role-based access requirements
- Restrict access to tables and fields
- Modify existing ACL configurations
- Test access using user impersonation
- Troubleshoot permissions using Debug Security Rules

## Hands-On Activities

### 1. Created an Access Control Rule

Created an ACL within the ServiceNow platform to control access to data.

Activities included:
- Navigating to Access Control configuration
- Creating an Access Control Rule
- Selecting the appropriate operation
- Configuring access requirements
- Saving the ACL configuration

**Navigation:**
All → System Security → Access Control (ACL)

### 2. Configured Role-Based Access

Configured role requirements within ACL rules to control which users could access protected resources.

Activities included:
- Reviewing available ServiceNow roles
- Assigning required roles to ACL configurations
- Examining how role requirements affect access
- Understanding role-based security principles

### 3. Restricted Table and Field Access

Worked with ACL configurations that restrict access to ServiceNow tables and fields.

Activities included:
- Configuring table-level access restrictions
- Configuring or examining field-level restrictions
- Understanding record and field access
- Reviewing access requirements for protected resources

### 4. Tested Security Using User Impersonation

Used ServiceNow's impersonation functionality to evaluate access from another user's perspective.

Activities included:
- Selecting a user for impersonation
- Navigating to protected platform resources
- Checking access behavior under the impersonated user's permissions
- Comparing expected permissions with observed behavior

### 5. Used Debug Security Rules

Used ServiceNow's Debug Security Rules functionality to investigate ACL evaluations.

Activities included:
- Enabling security debugging
- Reviewing ACL evaluation results
- Identifying rules involved in access decisions
- Investigating permission restrictions
- Using debugging information to understand security behavior

### 6. Modified an Existing ACL

Updated an existing Access Control Rule as part of the lab.

Activities included:
- Locating an existing ACL
- Reviewing its configuration
- Modifying access requirements
- Saving the changes
- Reviewing the effect of the updated rule

## Technical Concepts

| Concept | Description |
|---------|-------------|
| Access Control List (ACL) | Security rule controlling access to ServiceNow resources |
| Role-Based Access Control | Access management based on assigned roles |
| Table-Level ACL | Controls access to records within a table |
| Field-Level ACL | Controls access to individual fields |
| ACL Operations | Actions such as create, read, write, and delete |
| User Impersonation | Tests platform behavior from another user's perspective |
| Debug Security Rules | Helps investigate ACL evaluations and access decisions |
| Least Privilege | Security principle of granting only necessary access |

## ACL Evaluation

ServiceNow evaluates applicable ACL rules when users attempt to access protected resources.

ACL rules may include:
- Required roles
- Conditions
- Scripts

Table-level and field-level access rules can both affect whether a user can access a particular field.

Understanding these evaluations helps administrators troubleshoot permission issues and configure appropriate security restrictions.

## Skills Demonstrated

- ServiceNow Access Control Configuration
- ACL Creation and Modification
- Role-Based Access Management
- Table and Field Security
- User Impersonation
- Security Rule Debugging
- Access Troubleshooting
- Platform Security Fundamentals

## Real-World Application

These skills are relevant to ServiceNow administration in organizations that require controlled access to sensitive information.

For example, a healthcare organization may need to restrict medical equipment maintenance records to authorized employees.

ACLs can help enforce appropriate access restrictions for users responsible for equipment management, repair requests, and administrative functions.

## Challenges and Troubleshooting

The lab included testing access permissions and using Debug Security Rules to investigate ACL evaluations.

Specific troubleshooting examples and resolutions will be documented as supporting lab evidence is organized.

## Evidence of Hands-On Work

Planned supporting evidence:
- ACL configuration screenshot
- Role requirement screenshot
- Table or field access configuration
- User impersonation test
- Debug Security Rules output

Screenshots will be reviewed to ensure sensitive information is not publicly exposed.

## Key Takeaways

Through this lab, I gained practical experience creating, modifying, and testing ServiceNow Access Control Rules.

I strengthened my understanding of how roles, table-level security, field-level security, and ACL evaluations work together to control access to platform resources.

I also practiced using impersonation and security debugging tools to investigate access behavior.

## Lab Status

**Completed**

Documentation complete. Supporting screenshots and specific testing examples may be added.

## Program

ServiceNow RiseUp

## Related Skills

ServiceNow Administration | Access Control Lists | Role-Based Access Control | Security Troubleshooting | ITSM

