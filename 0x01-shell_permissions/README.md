# 0x01-shell_permissions

This directory contains shell scripts focused on file and directory permissions in Linux.

### Scripts:

- **0-iam_betty**          → Switches the current user to the user `betty`  
- **1-who_am_i**           → Prints the effective username of the current user  
- **2-groups**             → Prints all the groups the current user is a member of  
- **3-new_owner**          → Changes the owner of the file `hello` to the user `betty`  
- **4-empty**              → Creates an empty file called `hello`  
- **5-execute**            → Adds execute permission to the owner of the file `hello`  
- **8-James_Bond**         → Sets permissions on `hello`: owner & group = no permissions, others = all permissions (`-------rwx`)  
- **9-John_Doe**           → Sets permissions on `hello` to exactly `-rwxr-x-wx`  
- **11-directories_permissions** → Adds execute permission to all subdirectories (owner, group, and others); regular files unchanged  
- **12-directory_permissions** → Creates a directory named `my_dir` with permissions `751` (`drwxr-x--x`)  
- **13-change_group**      → Changes the group owner of the file `hello` to the group `school`

All scripts are written in Bash, start with `#!/bin/bash`, and are executable.
