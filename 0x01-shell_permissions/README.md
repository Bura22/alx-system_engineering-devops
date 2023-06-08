0) su betty: to switch the current user to the user betty.
1) whoami: to print the effective username of the current user.
2) groups: to print all the groups the current user is part of.
3) sudo chown betty hello: to change the owner of file hello to betty.
4) touch hello: to create an empty file called hello.
5) chmod u+x hello: to add execute permission to the owner of the file hello.
6) chmod u+x,g+x,o+r hello: to add execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7) chmod ugo+x hello: to add execution permission to the owner, the group owner and the other users, to the file hello.
8) chmod 007 hello: to add the permission to the file hello Owner: no permission at all, Group: no permission at all, Other users: all the permissions.
9) chmod 753 hello: to set ets the mode of the file hello.
10) chmod --reference=olleh hello: to set the mode of the file hello the same as olleh’s mode.
11) chmod -R ugo+X .: to add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12) mkdir -m 751 my_dir: creates a directory called my_dir with permissions 751 in the working directory.
13) chgrp school hello: to change the group owner to school for the file hello.
