su betty - script that switches the current user to the user betty
whoami-script that prints the effective username of the current user.
groups - script that prints all the groups the current user is part of.
chown -script that changes the owner of the file hello to the user betty.
touch - creates an empty file
chmod u+x hello -script that adds execute permission to the owner of the file hello.
chmod u+x,g+x,o+r hello - cript that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod a+x hello -script that adds execution permission to the owner, the group owner and the other users, to the file hello.
chmod o+rwx hello
chmod 007  hello :script that sets the permission to the file hello as follows:

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
chmod 752 hello -script that sets the mode of the file hello
chmod --reference=olleh hello- script that sets the mode of the file hello the same as olleh’s mode.
chmod -R ugo+X -script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
mkdir -m 751 my_dir-script that creates a directory called my_dir with permissions 751 in the working directory.

