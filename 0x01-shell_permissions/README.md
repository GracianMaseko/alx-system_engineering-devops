user betty: switches the current user to the user to betty 
id -u: prints the effective username of the current user
id: prints all the groups the current user is part of
chown betty hello: changes the owner of the file hello to the user betty
touch hello: Write a script that creates an empty file called hello
chmod u+x hello: adds execute permission to the owner of the file hello
chmod ug+x,o+r hello: adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod ugo+x hello: adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 07 hello: sets the permission to the file hello as - Owner: no permission at all; Group: no permission at all; Other users: all the permissions
chmod 753 hello: sets the mode of the file hello to -rwxr-x-wx
chmod --reference=olleh hello: sets the mode of the file hello the same as olleh’s mode
sudo chmod -R +111 */: adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
mkdir -m 751 my_dir: creates a directory called my_dir with permissions 751 in the working directory
