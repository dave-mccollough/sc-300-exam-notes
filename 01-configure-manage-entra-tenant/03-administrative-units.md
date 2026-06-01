# Administrative Units

- Administrative Units
  - Referred to as AUs
  - Same idea as AD Org Units
  - Containers in Entra ID for grouping users and devices
  - **They are not groups**
  - Allows you to divide tenant into smaller segments for more secure management
  - Example
    - Using AU for departments
      - Engineering Department AU
        - Seperates Engineering Department from ther departments

- Why Use AUs
  - Delegate access to only a part of the tenant/directory
  - Reduce risk by limiting admin permissions
  - Align tenant with org structure
  - Example
    - Engineering team can only reset passwords for Engineering AU, not entire company

- Use cases
  - Deparment based delegation
    - Each department can manage users and devices
  - Region or office based IT Management
    - Assign IT admins for geographic locations
  - Scoped help desk access
    - Help desk teams only have access to the users they are managing
  - School/University role seperation
    - Divide administration by location, campus, etc
  - Business unit isolation
    - Allow each business subsidiary to be managed independently
  - Secure access for temp workers or contractors
  
- Primary features of AUs
  - Scoped admin roles
  - Static membership
    - Users/devices can belong to multiple AUs if added manually
  - Dynamic membership
    - Users/devices can belong to only one AU if added with dynamic rules
  - AUs are not groups and can't be used for access control

- License requirements
  - AUs only require free Entra ID license
  - AU administrators must have Entra ID P1 license
  - AU members only requre free Entra ID license
  - If using dynamic rules to add members to AU, each member must have Entra ID P1 license

- Manage AUs
  - Navigate to `Administrative Units` in Azure, Entra, M365 admin portals
  - Add new AU
    - Restricted Management AU
      - Yes
        - Tenant level administrators will not have administrative permissions in this AU
      - No
        - Tenant level admins will have admin permissions in this AU
  - Add users to AU
  - Add groups to AU
  - add devices to AU
  - Setup dynamic membership rules