# Friday

1. useradd
What it does: Adds a new user to your system.
Key features:
Creates the user’s account.
Can also create a home folder for the user.
Example:
Add a user named john with a home directory:

useradd -m john
2. groupadd
What it does: Creates a new group in the system.
Why it’s useful: Groups make it easier to manage permissions for multiple users.
Example:
Create a group named developers:

groupadd developers
3. userdel
What it does: Deletes a user from your system.
Key feature: Can delete the user’s home folder if needed.
Example:
Delete a user john and their home directory:

userdel -r john
4. usermod
What it does: Modifies an existing user’s account.
Why it’s useful: Use it to:
Change a user’s home folder.
Add a user to a group.
Rename the user.
Example:
Add john to the sudo group:

usermod -aG sudo john
5. passwd
What it does: Manages user passwords.
Why it’s useful: Use it to:
Change a password.
Lock or unlock user accounts.
Example:
Set a password for john:

passwd john
6. su
What it does: Switches from one user account to another.
Why it’s useful: Allows you to temporarily act as another user (e.g., switch to the root user).
Example:
Switch to user john:

su - john
7. sudo
What it does: Runs commands with elevated (admin) privileges.
Why it’s useful: Lets you perform admin tasks without logging in as the root user.
Example:
Update the system (requires admin privileges):

sudo apt update
8. chage
What it does: Manages password expiration and account policies.
Why it’s useful: Ensures users update their passwords regularly or locks accounts after a certain period.
Example:
Set john’s password to expire every 90 days:

chage -M 90 john

