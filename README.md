Linux User & Group Management Script

Training project | Linux · Shell Scripting · System Administration

A shell script that automates the creation of a department structure on a Linux system — including group creation, user accounts, directory layout, permissions, and password policy. Written as a hands-on assignment for the system and network administration course at VDAB Wondelgem.

What It Does
Run with a single argument (the department folder name) and the script walks you through setting up a complete department environment interactively:

Creates a root directory and two subdirectories (RWdocs and ROdocs)
Creates a Linux group with a GID starting from 3000
Adds 2 regular users (UID from 2500) and 1 admin user (UID 5500–5600)
Sets ownership and permissions (775 / 750) with sticky bit on both directories
Enforces password change on first login and a 40-day password expiry
Generates a demodoc.txt log file with creation details, usernames and IDs


What I Learned

Linux user and group management (useradd, groupadd, getent, passwd, chage)
File permissions and ownership (chmod, chown, sticky bit)
Shell scripting fundamentals — argument validation, conditionals, input handling
Checking for existing users/groups before creating them to avoid conflicts
Why sudo/root privilege checks matter and how to implement them

