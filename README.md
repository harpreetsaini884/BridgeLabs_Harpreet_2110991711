# Monday

On Monday i have done the commands related to chmod,chown and Access control List(ACL)
and SUID and SGID.

1. chmod (Change Permissions)
Controls who can read, write, or execute a file.

Permissions:
Read (r) = 4, Write (w) = 2, Execute (x) = 1
Example:
chmod 755 file: Full access for owner, read/execute for group/others.
chmod u+x file: Adds execute permission to the owner.
2. chown (Change Ownership)
Sets the file's owner and group.

Examples:
Change owner: chown alice file
Change group: chown :team file
Recursive: chown -R alice:team folder
3. ACLs (Access Control Lists)
Fine-tune file access beyond basic permissions.

Commands:
View ACL: getfacl file
Add user/group access: setfacl -m u:john:rw file
Default ACLs: setfacl -d -m g:team:rwx folder
4. Special Permission Bits
Handle special cases for files and folders:

SUID (Set User ID)

Runs a file with the owner's permissions.
Set: chmod u+s file
Shown as s in owner’s execute bit (-rwsr-xr-x).
SGID (Set Group ID)

For programs: Runs with group permissions.
For folders: New files inherit the folder’s group.
Set: chmod g+s folder
Shown as s in group’s execute bit (-rwxr-sr-x).
Sticky Bit

Prevents users from deleting others’ files in shared folders.
Set: chmod +t folder
Shown as t in others’ execute bit (drwxrwxrwt).
