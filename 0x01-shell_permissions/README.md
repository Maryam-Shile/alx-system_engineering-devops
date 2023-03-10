
su changes file owner to betty
whoami prints the effective username of current user
groups prints all groups a user is part of
sudo chown changes the owner of file hello to betty
touch created an empty file hello
chmod u+x adds execute permission to the file owner hello
chmod u+x,g+x,o=r adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod a+x hello adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 sets permission only to the other users
chmod 753 that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
chmod --reference=olleh hello changed the permission of hello to be identical to olleh
chmod -R a+x . changed the permission of only sub directories
