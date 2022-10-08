'pwd' is to print the absolute path name of the current working directory

'ls' is the command to display the contents list of you current directory

'cd' is the command  to change the working directory to the user's home directory

'ls -l' is the command to display the current directory's contents in a long format

'ls -la' is the command to display the current directory's contents including hidden files in a long format

'ls -lna' is the command the current directory's content in a long format with user and group id's displayed numerically and hidden files too

'mkdir /tmp/my_first_directory' is the command to create the named directory in the /tmp/ directory

'mv /tmp/betty /tmp/my_first_directory is the command used to move the file betty to the directory stated

'rm /tmp/my_first_directory/betty' is the command used to delete the file betty from its directory

'rm -r /tmp/my_first_directory' is the command to delete the stated directory

'cd -' is the command to change the working directory to the previous one

'ls -la . .. /boot' is a command that that lists all files including the hidden ones in the current directory, the parent of the working directory and the /boot directory in this order, in the long format

'file /tmp/iamafile' is a command that prints the type of the file mentioned which is in the /tmp directory when running the command

'ln -s bin/ls ___ls___' is a command that creates a symbolic link to /bin/ls named _ls_ this link should be in the current working directory

'cp -u *.html ..' is a command that copies all the html files from the current working directory to the parent of the current working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory 

'mv [[:upper:]]* /tmp/u' is a command that moves all files beginning with an uppercase letter to the '/tmp/u' directory

'rm *~' is the command that deletes all files in the current working directory ending with '~'

'mkdir -p welcome/to/school' is a command that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory

'ls -xamp' lists all the files and directories in the current directory, separated by commas

'0	string SCHOOL School data
!:mime school
 creates a magic file with the stated name that can be used with the command file to detect school data files
