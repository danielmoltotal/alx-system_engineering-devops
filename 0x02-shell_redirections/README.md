#Shell, I/O Redirections and Filters Exercises

Exercise 0: prints “Hello, World”, followed by a new line to the standard output.

Exercise 1: displays a confused smiley "(Ôo)'.

Exercise 2: dsplays the content of the /etc/passwd file.

Exercise 3: displays the content of /etc/passwd and /etc/hosts.

Exercise 4: displays the last 10 lines of /etc/passwd.

Exercise 5: displays the first 10 lines of /etc/passwd.

Exercise 6: displays the third line of the file iacta.

Exercise 7: creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

Exercise 8: writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

Exercise 9: duplicates the last line of the file iacta.

Exercise 10: deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

Exercise 11: counts the number of directories and sub-directories in the current directory. The current and parent directories are not taken into account. And hidden directories are counted.

Exercise 12: displays the 10 newest files in the current directory.

Exercise 13: takes a list of words as input and prints only words that appear exactly once. Input format: One line, one word. Output format: One line, one word. Words should be sorted.

Exercise 14: displays lines containing the pattern “root” from the file /etc/passwd.

Exercise 15: displays the number of lines that contain the pattern “bin” in the file /etc/passwd.

Exercise 16: displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

Exercise 17: displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.

Exercise 18: displays all lines of the file /etc/ssh/sshd_config starting with a letter.

Exercise 19: replaces all characters A and c from input to Z and e respectively.

Exercise 20: removes all letters c and C from input.

Exercise 21: reverses its input.

Exercise 22: displays all users and their home directories, sorted by users.

Exercise 23:  finds all empty files and directories in the current directory and all sub-directories. Only the names of the files and directories should be displayed (not the entire path). Hidden files should be listed. One file name per line. The listing should end with a new line. You are not allowed to use basename, grep, egrep, fgrep or rgrep.

Exercise 24: lists all the files with a .gif extension in the current directory and all its sub-directories. Hidden files should be listed. Only regular files (not directories) should be listed. The names of the files should be displayed without their extensions. The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay). One file name per line. The listing should end with a new line. You are not allowed to use basename, grep, egrep, fgrep or rgrep.

Exercise 25: creates a script that decodes acrostics that use the first letter of each line. n acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval

Exercise 26: parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Order by number of requests, most active host or IP at the top. You are not allowed to use grep, egrep, fgrep or rgrep.
