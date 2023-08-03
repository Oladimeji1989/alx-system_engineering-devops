# 0x01. Shell, permissions

## Describing what each script is doing
* su betty  switch user to betty
* whoami prints the effective username of the current user
* groups prints all the groups the current user is part of
* chown betty hello, change hello file to betty
* chmod u+X hello change execution right
* touch hello create empty file hello
* chmod Ug+x,o+r hello  execute permission to the owner and the group owner, and read permission to other users, to the file hello
* chmod ugo+x hello permission to the owner, the group owner and the other users, to the file hello
* chmod 007 Other users: all the permissions only

