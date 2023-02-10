This directory contains scripts that alters the permissions of files.
0-iam_betty switches the current user to the user betty
1-who_am_i prints the effective username of the current user
2-groups script prints all the groups the current user is part of
3-new_ownerscript changes the owner of the file hello to the user betty
4-empty script creates an empty file called hello
5-execute script adds execute permission to the owner of the file hello
6-multiple_permissions script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
7-everybody script adds execution permission to the owner, the group owner and the other users, to the file hello
8-James_Bond script removes all permissions from the owner and group owner and gives full permission to other users of the file hello
9-John_Doe script sets mode of the file hello to -rwxr-x-wx
10-mirror_permissions script sets the mode of the file hello the same as olleh's mode
11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users, excluding regular files
12-directory_permissions script creates a directory called my_dir with permissions 751 in the working directory
13-change_group script changes the group owner of the file hello to school
