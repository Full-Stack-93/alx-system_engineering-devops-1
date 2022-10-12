Task 0 - Print Hello world with 'echo "Hello World" 

Task 1 - Print a confused smiley with 'echo "\"(Ôo)'"

Task 2 - Display contents of the file '/etc/passwd' with 'cat /etc/passwd'

Task 3 - Display the contents of the files '/etc/passwd' and '/etc/hosts' with 'cat /etc/passwd /etc/hosts'

Task 4 - Display the last ten lines of '/etc/passwd' with 'tail-10 /etc/passwd'

Task 5 - Display the first ten lines of '/etc/passwd' with 'head -10 /etc/password'

Task 6 - Displays the third line of the file 'iacta' with 'head -3 iacta | tail +3' or 'head --lines=3 iacta | tail --lines=1'

Task 7 - Create a file named exactly '\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)' containing the text 'Best School' ending by a new line with 'echo "Best School" > \\\*\\\\\'\"Best\ School\"\\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)'

Task 8 -Write into the file 'ls_cwd_content' the result of the command 'ls -la'. If the file 'ls_cwd_content' already exists, it should be overwritten. If the file 'ls_cwd_content' does not exist, create it

Task 9 -Duplicate the last line of the file 'iacta' with 'tail --lines=1 iacta >> iacta'

TasK 10 - Delete all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders with 'find . -name '*.js' -type f -delete'

Task 11 - Count the number of directories and sub-directories in the current directory.
The current and parent directories should not be taken into account
Hidden directories should be counted with 'find -mindepth 1 -type d | wc -l'

Task 12 - Create a script that displays the 10 newest files in the current directory. Requirements: One file per line, Sorted from the newest to the oldest with 'ls -t | head'

Task 13 - Take a list of words as input and print onlywords that appear exactly once. Input format: One line, one word. Output format: One line, one word. Words should be sorted with 'sort | uniq -u'

Task 14 - Display lines containing the pattern “root” from the file '/etc/passwd' with 'grep -i "root" /etc/passwd'

Task 15 - Display the number of lines that contain the pattern “bin” in the file '/etc/passwd' with 'grep -c "bin" /etc/passwd'

Task 16 - Display lines containing the pattern “root” and 3 lines after them in the file '/etc/passwd' with 'grep -iA 3 "root" /etc/passwd'

Task 17 - Display all the lines in the file '/etc/passwd' that do not contain the pattern “bin” with 'grep -v "bin" /etc/passwd'

Task 18 - Display all lines of the file '/etc/ssh/sshd_config' starting with a letter. Include capital letters as well with 'grep '^[A-Za-z]' /etc/ssh/sshd_config'

Task 19 - Replace all characters 'A' and 'c' from input to 'Z' and 'e' respectively with 'tr Ac Ze'

Task 20 - Create a script that removes all letters 'c' and 'C' from input with 'tr -d cC'

Task 21 - Write a script that reverse its input with 'rev'

Task 22 - Write a script that displays all users and their home directories,sorted by users. Based on the the '/etc/passwd' file with 'cut -d':' -f1,6 /etc/passwd | sort'

Task 23 - Find all empty files and directories in the current directory and all sub-directories.
Only the names of the files and directories should be displayed (not the entire path). Hiddenfiles should be listed. One file name per line. The listing should end with a new line. You are not allowed to use basename, grep, egrep, fgrep or rgrep with
"find . -empty -printf %f'\n'" or "find . -empty -printf "%f\n""

Task 24 -  lists all the files with a .gif extension in the current directory and all its sub-directories.
Hidden files should be listed
Only regular files (not directories) should be listed
The names of the files should be displayed without their extensions
The files should be sorted by byte values, but case-insensitive (file 'aaa' should be listed before file 'bbb', file '.b' should be listed before file 'a', and file 'Rona' should be listed after file 'jay').
One file name per line. 
The listing should end with a new line.
You are not allowed to use basename, grep, egrep, fgrep or rgrep 
with 'find . -type f -name \*.gif -printf "%f\n" | LC_ALL=C sort -f | rev | cut -b 5- | rev'

Task 25 - An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieva.
Create a script that decodes acrostics that use the first letter of each line.
The ‘decoded’ message has to end with a new line
You are not allowed to use grep, egrep, fgrep or rgrep
with "cut -c 1 | paste -s -d ''"

Task 26 - Parse web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
Order by number of requests, most active host or IP at the top
You are not allowed to use grep, egrep, fgrep or rgrep
with 'tail -n +2 | cut -f1 | sort | uniq -c | sort -nr | head -11 | tr -s ' ' | cut -d' ' -f3'
