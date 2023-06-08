su betty: to switch the current user to the user betty.
whoami: to print the effective username of the current user.
groups: to print all the groups the current user is part of.
sudo chown betty hello: to change the owner of file hello to betty.
touch hello: to create an empty file called hello.
chmod u+x hello: to add execute permission to the owner of the file hello.
chmod u+x,g+x,o+r hello: to add execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello: to add execution permission to the owner, the group owner and the other users, to the file hello.
chmod 007 hello: to add the permission to the file hello Owner: no permission at all, Group: no permission at all, Other users: all the permissions.
chmod 753 hello: to set ets the mode of the file hello.
chmod --reference=olleh hello: to set the mode of the file hello the same as olleh’s mode.
chmod -R ugo+X: to add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
mkdir -m 751 my_dir: creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello: to change the group owner to school for the file hello.
