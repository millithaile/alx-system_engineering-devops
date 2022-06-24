Shell Permission Exercise:

Task 0: su betty, command will switch current user to betty.

Task 1: id -un, command print current username.

Task 2: id -Gn, command will print all group which is part of current user.

Task 3: chown betty hello, command will change file hello owner to user betty.

Task 4: touch hello,  command creates empty file hello.


Task 5: chmod u+x hello, command makes hello file executable permission.

Task 6: chmod ugo+x,o+r hello, command gives execution permission to currentuser, group, and read permission to other users.

Task 7: chmod ugo+x hello, command gives permission to owner, group and other users.

Task 8: chmod 007 hello, command set no permission to hello file for owner, group and other.

Task 9: chmod 753 hello, command sets permission for owner to execute, read and write, and sets group to read and execute, others users write and execute permissions on hello file.

Task 10: chmod --reference olleh hello, copies mode from olleh file to hello file.

Task 11: adds execution permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

Task 12: mkdir -m 751 my_dir creates a directory with a permission of 751.

Task 13: chgr school hello, command changes group owner to hello.

Task 14: Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Task 15: chown -h vincent:staff _hello, command changes the owner and the group owner of _hello to vincent and staff respectively.

Task 16: chown --from=guillaume betty hello, command changes the owner of the file hello to betty only if it is owned by the user guillaume.

Task 17: telnet towel.blinkenlights.nl , play starwars.

