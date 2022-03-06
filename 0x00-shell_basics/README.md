#Shell Scripting Basics Exercises

Exercise 0: pwd ===> print absolute path name of current working directory.

Exercise 1: ls ===> display contents list of current working directory.

Exercise 2: cd ===> change the working directory to the user’s home directory.

Exercise 3: ls -l ===> display current directory contents in a long format.

Exercise 4: ls -la ===> display current directory contents, including hidden files (starting with .). Use the long format.

Exercise 5: ls -la ===> display current directory contents. Note: Are files inherently ordered?

Exercise 6: mkdir /tmp/my_first_directory ==> create a directory named my_first_directory in the /tmp/ directory.

Exercise 7: mv /tmp/betty /tmp/my_first_directory ==> move the file betty from /tmp/ to /tmp/my_first_directory.

Exercise 8: rm /tmp/my_first_directory/betty ===> delete the file betty.

Exercise 9: rm -r /tmp/my_first_directory ==> delete the directory my_first_directory that is in the /tmp director.

Exercise 10: cd - ===> change directory to the previous directory you were in.

Exercise 11: ls -l -a . .. /boot ===> list all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format. The ls command allows multiple directories to be listed separated by spaces.

Exercise 12: file /tmp/iamafile ===> print the type of the file named iamafile.

Exercise 13: ln -s /bin/ls ./__ls__ ===> create a symbolic link named _ls_ for /bin/ls.

Exercise 14: cp -u ./*.html ../ ===> copy all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.

Exercise 15: mv [[:upper:]]* /tmp/u ===> move all the files beginning with an uppercase letter to the directory /tmp/u.

Exercise 16: rm ./*~ ===> delete all the files in the current working directory that end with the character ~. Can ommit the ./ part though.

Exercise 17: mkdir -p welcome/to/school ===> create the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

Exercise 18: ls -pma ===> list all the files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

Exercise 19: ===> create a magic file called school.mgc that can be used with the command file to detect School data files. School data files always contain "SCHOOL" at offset 0.
