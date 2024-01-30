# User and Group Management Guide

## 1. Add User - `useradd`

     sudo useradd researcher9
## 2. Append Recent Permissions - usermod

     sudo usermod -g research_team researcher9
## 3. Change Ownership - chown

     sudo chown researcher9 /home/researcher2/projects/project_r.txt
## 4. Add User to Secondary Group - usermod

     sudo usermod -a -G sales_team researcher9
## 5. Delete User - userdel

     sudo userdel researcher9
## 6. Remove from Group - groupdel

     sudo groupdel researcher9
## Note: Use sudo to execute these commands with the necessary privileges. Double-check group names and file paths before executing the commands to avoid unintended changes.
