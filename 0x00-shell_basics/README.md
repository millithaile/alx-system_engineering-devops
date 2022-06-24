Shell Basic Exercise:

Task 0: pwd, script print absolute current working diretory path name.

Task 1: ls, script lists content in working directory.

Task 2:  cd, Script changes the working directory to users home directory.

Task 3: ls -l , Script display current directory content in a long format.

Task 4:  ls -la, Script display current directory contents, including hidden files in long format.

Task 5:  ls -na,Script display current directory contents 

Task 6: mkdir /tmp/my_first_directory, script creates a directory named my_first_directory in the /tmp/ directory.

Task 7: mv /tmp/betty /tmp/my_first_directory, script moves the file betty from /tmp/ to /tmp/my_first_directory.

Task 8: rm /tmp/my_first_directory/betty, script deletes the file betty.

Task 9: rm -r /tmp/my_first_directory, script deletes the directory my_first_directory that is in the /tmp directory.

Task 10: cd -, changes the working directory to the previous one.

Task 11: ls -al . .. /boot, script lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

Task 12: file /tmp/iamafile , script prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

Task 13: ln -s /bin/ls ls , creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

Task 14: cp -rua *.html ../ , script copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
Task 15:  mv [[:upper:]]* /tmp/u , script moves all files beginning with an uppercase letter to the directory /tmp/u.

Task 16: rm *~ , script deletes all files in the current working directory that end with the character ~.

Task 17: mkdir -p welcome/to/school , script creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

Task 18: ls -map | sort -d , script lists all the files and directories of the current directory, separated by commas (,).

Task 19:  0 string SCHOOL School data  !:mime School , script creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

