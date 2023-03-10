script that switches the current user to the user betty : su bettY
script that prints the effective username of the current user : id -un
script that prints all the groups the current user is part of : groups
script that changes the owner of the file hello to the user betty : chown betty hello
script that adds execute permission to the owner of the file hello : chmod u+x hello
script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello : chmod ug+x,o+r hello
script that adds execution permission to the owner, the group owner and the other users, to the file hello : chmod ugo+x hello
 script that sets the permission to the file hello/ Owner: no permission at all/Group: no permission at all/Other users: all the permissions : chmod 077 hello
