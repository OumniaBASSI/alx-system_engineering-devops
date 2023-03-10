script that switches the current user to the user betty : su bettY
script that prints the effective username of the current user : id -un
script that prints all the groups the current user is part of : groups
script that changes the owner of the file hello to the user betty : chown betty hello
script that adds execute permission to the owner of the file hello : chmod u+x hello
script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello : chmod ug+x,o+r hello
script that adds execution permission to the owner, the group owner and the other users, to the file hello : chmod ugo+x hello
 script that sets the permission to the file hello/ Owner: no permission at all/Group: no permission at all/Other users: all the permissions : chmod 077 hello
script that sets the mode of the file hello to The file hello will be in the working directory/You are not allowed to use commas for this script : chmod 753 hello
script that sets the mode of the file hello the same as olleh’s mode/The file hello will be in the working directory/The file olleh will be in the working directory :chmod --reference=olleh hello
script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users : chmod -R a+X */
script that creates a directory called my_dir with permissions 751 in the working directory : mkdir -m 751 my_dir
script that changes the group owner to school for the file hello/The file hello will be in the working directory : chgrp school hello
 script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory : chown -R vincent:staff *
Write a script that changes the owner and the group owner of _hello to vincent and staff respectively/The file _hello is in the working directory/The file _hello is a symbolic link : chown -h vincent:staff _hello
