Task 0 - Create a script that creates an alias.
Name: ls
Value: rm *
Script: alias ls="rm *"

Task 1 - Create a script that prints hello user, where user is the currentLinux user.
Script: echo "hello $USER"

Task 2 - Add '/action' to the 'PATH'. '/action' should be the last directory the shell looks into when looking for a program.
Script: PATH=$PATH:/action

Task 3 - Create a script that counts the number of directories in the PATH
Script: echo $PATH | tr ":" "\n" | wc -l

Task 4 - Create a script that lists environment variables.
Script: printenv

Task 5 - Create a script that lists all local variables and environment variables, and functions.
Script: set | less

Task 6 - Create a script that creates a new local variable.
Name: BEST
Value: School
Script: export BEST="School"

Task 7 - Create a script that creates a new global variable.
Name: BEST
Value: School
Script: export BEST="School"

Task 8 - Write a script that prints the result of the addition of 128 with the value stored in the environment variable 'TRUEKNOWLEDGE', followed by a new line.
Script: echo $(($TRUEKNOWLEDGE+128))
