'su betty' is the command used to change the current user to betty

'id -u -n' is the command used to print the username of the current user

'groups' is the command for printing all the groups the current user is part of

'chown betty hello' is the command for changing the ownership odf the file 'hello' to betty

'touch hello' is a command for creating an empty file 'hello'

'chmod u+x hello' is the command for adding execute permission to the owner of the file 'hello'

'chmod u+x,g+x,o+r hello' is the command for adding execute permissions to the owner and the group owner and read permission to other users

'chmod ugo+x hello' is the command to add execute permission to the owner, the group owner and other users

'chmod 007 hello' is the command to give the owner and group owner no permissions and the users all the permissions

'chmod 753 hello' is the command for the task 9

'chmod --reference=olleh hello' is the command for setting the mode of the file 'hello' the same as the file olleh

'chmod a+x +/' is the command for adding execute permissions to all subdirectories of the current directory for the owner, the group oner and other users

'mkdir -m 751 my_dir' is the command for creating a directory with permission 751 in the working directory

'chgrp school hello' is the command for changing the group owner to school for the file 'hello'

'chown vincent:staff * 100-change_own_and_group working' is the command for changing the owner to vincent and the group owner to staff for all the files and directories in the working directory

'chown vincent:staff _hello' is the command for changing the owner and group owner of hello to vincent and staff respectively

'chown -from=guillaume betty hello' is the command for changing the owner of the file 'hello' to betty only if it is owned by the user guillaume

'telnet towel.blinkenlight.nl' is the command for playing the StarWars IV episode in the terminal
