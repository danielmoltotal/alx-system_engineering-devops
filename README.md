Shell basics

0. Write a script that prints the absolute path name of the current working directory.
1. Display the contents list of your current directory.
2. Write a script that changes the working directory to the user’s home directory.
3. Display current directory contents in a long format
4. Display current directory contents, including hidden files (starting with .). Use the long format. 
5. Display current directory contents. Long format with user and group IDs displayed numerically And hidden files (starting with .) 
6. Create a script that creates a directory named holberton in the /tmp/ directory. 
7. Move the file betty from /tmp/ to /tmp/my_first_directory. 
8. Delete the file betty.The file betty is in /tmp/my_first_directory. 
9. Delete the directory my_first_directory that is in the /tmp directory. 
10. Write a script that changes the working directory to the previous one. 
11. Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the           working directory and the /boot directory, in long format. 
12. Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script. 
13. Create a symbolic link to /bin/ls, named _ls_. The symbolic link should be created in the current working directory. 
14. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the           parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension .html 
15. Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u. You can assume that the directory /tmp/u will exist when we will run your       script 
16. Create a script that deletes all files in the current working directory that end with the character ~. 
17. Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces in your script,         not more. 
18. List all the files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.)     or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option       streams the output, separating each listing with commas. 
19. Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0. school.mgc     has to be created on Ubuntu 20.04.

Shell Permissions

0. Create a script that changes your user ID to betty.
1. Write a script that prints the effective user ID of current user. Other alternative is whoami
2. Write a script that prints all the groups the current user is part of.
3. Write a script that changes the owner of the file hello to the user betty
4. Write a script that creates an empty file called hello
5. Write a script that adds execute permission to the owner of the file hello
6. Write a script that adds execute permission to user and group owner, and read permission to others for file hello
7. Write a script that adds execution permission to all for file hello.
8. Write a script that sets permissions for file hello so owner and group don't have any permissions and other users have all permissions.
9. Write a script that sets permissions so owner has all permissions, group has read and execute permissions and others have write and execute permissions.
10. Write a script that copies the mode of file olleh to file hello.
11. Create a script that adds execute permission to all subdirectories of the current directory for the everyone. Regular files should not be changed.
12. Create a script that creates a directory called my_dir with permissions 751 in the working directory. User has all read, write, and execute permissions. Group has read and       execute permissions. Others have just execute permission.
13. Write a script that changes gorup owner to school for the file hello
14. Write a script that changes owner to vincent and the group owner to staff for all files and directories in current directory.
15. Write a script that changes the owner and group owner of file _hello to vincent and staff respectively.
16. Write a script that changes owner of the file hello to betty only if it is currently owned by guillaume
17. Write a script that plays the Star Wars IV episode in the terminal. This is a premade script provided online.
