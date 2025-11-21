Shell Permissions Project
This repository contains a collection of shell scripts for learning and practicing Linux shell permissions and user/group management.

Project Structure

system_engineering-devops/
└── 0x01-shell_permissions/
    ├── 0-iam_betty
    ├── 1-who_am_i
    ├── 2-groups
    ├── 3-new_owner
    ├── 4-empty
    ├── 5-execute
    ├── 8-James_Bond
    ├── 9-John_Doe
    ├── 11-directories_permissions
    ├── 12-directory_permissions
    └── 13-change_group
Scripts Description
0. My Name Is Betty
File: 0-iam_betty
Switches the current user to the user named betty. The command is exactly 8 characters long.

1. Who Am I
File: 1-who_am_i
Prints the effective username of the current user.

2. Groups
File: 2-groups
Prints all the groups the current user is part of.

3. New Owner
File: 3-new_owner
Changes the owner of the file hello to the user betty.

4. Empty!
File: 4-empty
Creates an empty file called hello.

5. Execute
File: 5-execute
Adds execute permission to the owner of the file hello.

6. James Bond
File: 8-James_Bond
Sets the permissions for the file hello as follows:

Owner: no permissions

Group: no permissions

Others: all permissions (read, write, execute)

7. John Doe
File: 9-John_Doe
Sets the permissions for the file hello to -rwxr-x-wx.

8. Directories
File: 11-directories_permissions
Adds execute permission to all subdirectories of the current directory for all users.

9. More Directories
File: 12-directory_permissions
Creates a new directory called my_dir with permissions 751.

10. Change Group
File: 13-change_group
Changes the group owner of the file hello to the group school.

Usage
All scripts are executable Bash scripts. To run any script:

./script_name
Some scripts may require elevated privileges (using sudo) to execute properly.

Requirements
All scripts start with #!/bin/bash

All scripts are executable

File names match exactly as specified

Scripts follow the exact requirements for each task

Author
This project is part of the system engineering and DevOps curriculum.

License
This project is for educational purposes as part of a curriculum.
