0. su betty - changes the owner of the file
1. whoami - Write a script that prints the effective username of the current user.
2. id -nG - prints all the groups the current user is part of
3. sudo chown - changes the owner of the file
4. touch - creates and empty file
5. chmod 744 - adds the execute permission to the file owner
6. chmod 754 hello - adds execute permission to the owner and the group owner, and read permission to other users
7. chmod a+x hello - adds execution permission to the owner, the group owner and the other users, to the file
8. chmod 007 hello - sets the permission to the file hello Owner: no permission at all Group: no permission at all Other users: all the permissions
9. chmod 753 hello - changes the mode of the file to -rwxr-x-wx
10. chmod --reference=olleh hello - sets the mode of the file hello the same as olleh’s mode
11. chmod -R a+X . - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
12. mkdir -m 751 my\_dir - creates a directory called my\_dir with permissions 751 in the working directory.
13. chgrp school hello - changes the group owner to school for the file hello
14. chown vincent:staff * - changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15. chown -h vincent:staff _hello - changes the owner and the group owner of _hello to vincent and staff respectively
16. chown --from=guillaume betty hello - changes the owner of the file hello to betty only if it is owned by the user guillaume.
17. telnet towel.blinkenlights.nl - script that will play the StarWars IV episode in the terminal.
