the 0-iam_betty script switches the current user to the user betty
the 1-who_am_i script prints the effective username of the current user.
the 2-groups scripts prints all the groups the current user is part of.
the 3-new_owner script changes the owner of the file hello to the user betty.
the 4-empty script  creates an empty file called hello.
the 5-execute script  adds execute permission to the owner of the file hello.
the 6-multiple_permissions script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
the 7-everybody script adds execution permission to the owner, the group owner and the other users, to the file hello
the 8-James_Bond script sets the permission to the file hello as follows:

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
the 9-John_Doe script sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
the 10-mirror_permissions script sets the mode of the file hello the same as olleh’s mode.
the 11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
the 12-directory_permissions script creates a directory called my_dir with permissions 751 in the working directory.
the 13-change_group script changes the group owner to school for the file hello
