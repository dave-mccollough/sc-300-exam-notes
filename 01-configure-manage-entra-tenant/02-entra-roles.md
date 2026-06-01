# Microsoft Entra Roles

- User capabilities
  - Roles define what users can do within Microsoft services
- Least Privilege
  - Based on principles of least privilege
  - Ensure users only have necessary access rights
- RBAC focused
  - Central to RBAC
- Service Integration
  - Used in Azure, M365 and Entra to control access

- Azure RBAC roles (Resource focused)
  - Role based access controls permissions
  - Manage who can access Azure resources and at what scope
    - Management group
    - Subscription
    - Resource group
    - Specific resource
  - Primary role types
    - Full Access to least access
      - Owner - Full access, including the ability to assgin roles
      - Contributor - Create and manage resources (no RBAC)
      - Reader - View only access
      - Custom Roles - Define specific permissions

- Entra ID roles (Formerly Azure AD Roles) (Identity focused)
  - Predefined sets of permissions
  - Control access to identity and directory resources across M365 and Azure Environments
  - Roles can be assgined to users, groups, or service principles
  - Primary role types
    - Global Administrator - Full control access Entra ID
    - User Administrator - Manage users and groups
    - Security Reader/Administrator - View and manage security settings
    - Cloud Application Administrator - Manage app registrations and configurations

- Microsoft 365 Roles (Application focused)
  - Built in adminstrative roles that grant users or groups permissions to manage Exchange, SharePoint, Teams and other M365 services
  - Primary role types
    - Global admin - Full access
    - Exchange admin - Full management access for Exchange
    - SharePoint admin - Full management access for SharePoint 
    - Teams admin - Full management access for Teams
    - Compliance admin - Full management access to Purview

- Principle of least privilege
  - Give user the least amount of rights to allow them to do their job
  - When used with PIM (Privelege Idenity Management), you can get JIT (Just in Time) administration using roles

- **Best Practices**
  - Assign roles to groups, not users
  - Follow least privilege
  - Regularly review role assignments

## Entra Built in Roles

- [Link](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/permissions-reference)
