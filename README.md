# Tuesday

Today we have Scenario based question on chmod,chown,ACL's and SUIS AND GUID

Scenario 1: Department Directories
You are a system administrator managing directories for different departments in your organization. Each department has specific access requirements.

Requirements:

Create a shared directory /departments with subdirectories for hr, finance, and engineering.
Group hr_team should have full access to /departments/hr.
Group finance_team should have read and execute permissions on /departments/finance but cannot modify or delete files.
Group engineering_team should have full access to /departments/engineering.
User manager should have read and write permissions across all department directories.
Ensure that any new files created in /departments inherit the correct permissions.
Tasks:

Set up the directories and apply the appropriate permissions using ACL.
Verify that default ACLs are configured correctly.

//--------------------------------------------------------------------

Scenario 2: Shared Project Repository
Your company uses a shared repository for collaborative projects.

Requirements:

Create a directory /repo with subdirectories team_alpha, team_beta, and team_gamma.
Group alpha_team should have full access to /repo/team_alpha.
Group beta_team should have read-only access to /repo/team_beta.
Both alpha_team and beta_team should have read and execute permissions on /repo/team_gamma.
User lead_dev should have full access to all subdirectories.
Set up default permissions for new files and directories.
Tasks:

Configure ownership, permissions, and ACLs for /repo and its subdirectories.
Test the access levels by simulating different users.
