su betty script that switches the current user to the user betty.
whoami script that prints the effective username of the current user.
groups script that prints all the groups the current user is part of.
sudo chown betty hello script that changes the owner of the file hello to the user betty.
touch hello  script that creates an empty file called hello.
chmod u+x hello script that adds execute permission to the owner of the file hello.
chmod u+x,g+x,o+r hello script that adds execute permission to the owner and the group owner, and read permission to other users, to the file.
chmod u+x,g+x,o+x hello script that adds execution permission to the owner, the group owner and the other users, to the file hello.
chmoe 007 hello script that sets the permission to the file hello as follows:Owner: no permission at all Group: no permission at allOther users: all the permissions
chmod 753 hello script that sets the mode of the file hello to this:-rwxr-x-wx
chmod --reference=olleh hello Write a script that sets the mode of the file hello the same as olleh’s mode.
chnod -R +111 */ Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
mkdir -m 751 my_dir Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
chgrp hello school Write a script that changes the group owner to school for the file hello
chown vincent:staff * Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown -h vincent:staff _hello Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.
