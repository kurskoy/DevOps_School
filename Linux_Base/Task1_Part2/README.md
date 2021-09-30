##Task1.Part2

1. Examine the tree command. Master the technique of applying a template, for
example, display all files that contain a character c, or files that contain a
specific sequence of characters. List subdirectories of the root directory up to
and including the second nesting level.
2. What command can be used to determine the type of file (for example, text or
binary)? Give an example.
3. Master the skills of navigating the file system using relative and absolute paths.
How can you go back to your home directory from anywhere in the filesystem?
4. Become familiar with the various options for the ls command. Give examples
of listing directories using different keys. Explain the information displayed on
the terminal using the -l and -a switches.

![tree_file_pwd_home](tree_file_pwd_home.png)
5. Perform the following sequence of operations:
- create a subdirectory in the home directory;
- in this subdirectory create a file containing information about directories
located in the root directory (using I/O redirection operations);
- view the created file;
- copy the created file to your home directory using relative and absolute
addressing.
- delete the previously created subdirectory with the file requesting removal;
- delete the file copied to the home directory.

![directory_info_rm_files](directory_info_rm_files.png)
6. Perform the following sequence of operations:
- create a subdirectory test in the home directory;
- copy the .bash_history file to this directory while changing its name to
labwork2;
- create a hard and soft link to the labwork2 file in the test subdirectory;
- how to define soft and hard link, what do these
concepts;
- change the data by opening a symbolic link. What changes will happen and
why
- rename the hard link file to hard_lnk_labwork2;
- rename the soft link file to symb_lnk_labwork2 file;
- then delete the labwork2. What changes have occurred and why?

![cp_ln_lns](cp_ln_lns.png)

![rename_delete_lnk](rename_delete_lnk.png)
7. Using the locate utility, find all files that contain the squid and traceroute
sequence.

![locate_find](locate_find.png)
8. Determine which partitions are mounted in the system, as well as the types of
these partitions.

![lsblk_mounts](lsblk_mounts.png)
9. Count the number of lines containing a given sequence of characters in a given
file.

![wc](wc.png)
10. Using the find command, find all files in the /etc directory containing the
host character sequence.

![find_host](find_host.png)
11. List all objects in /etc that contain the ss character sequence. How can I
duplicate a similar command using a bunch of grep?

![ss](ss.png)