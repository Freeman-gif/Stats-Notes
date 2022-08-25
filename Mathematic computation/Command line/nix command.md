
# nix command


---
### Notes and Ideas:

- ls -lists the content of a directoru
- pwd - print working directory
- cd -change directory
- MKDIR - make a new directory
- rm - removes files
- rmdir - removes directory, the directory must be empty of files or other directories
- mv - move a file to another with a different name 
- cp - copy
- man - accesses the systemes manual
-     **-@**      Display extended attribute keys and sizes in long (**-l**) output.

  

     **-A**      Include directory entries whose names begin with a dot (‘.’) except for . and ...  Automatically set for the super-user unless **-I** is specified.

  

     **-B**      Force printing of non-printable characters (as defined by ctype(3) and current locale settings) in file names as \xxx, where xxx is the numeric value of the character in

             octal.  This option is not defined in IEEE Std 1003.1-2008 (“POSIX.1”).

  

     **-C**      Force multi-column output; this is the default when output is to a terminal.

  

     **-D** format

             When printing in the long (**-l**) format, use format to format the date and time output.  The argument format is a string used by strftime(3).  Depending on the choice of

             format string, this may result in a different number of columns in the output.  This option overrides the **-T** option.  This option is not defined in IEEE Std 1003.1-2008

             (“POSIX.1”).

  

     **-F**      Display a slash (‘/’) immediately after each pathname that is a directory, an asterisk (‘*’) after each that is executable, an at sign (‘@’) after each symbolic link, an

             equals sign (‘=’) after each socket, a percent sign (‘%’) after each whiteout, and a vertical bar (‘|’) after each that is a FIFO.

  

     **-G**      Enable colorized output.  This option is equivalent to defining CLICOLOR or COLORTERM in the environment and setting **--color**=auto.  (See below.)  This functionality can

             be compiled out by removing the definition of COLORLS.  This option is not defined in IEEE Std 1003.1-2008 (“POSIX.1”).

  

     **-H**      Symbolic links on the command line are followed.  This option is assumed if none of the **-F**, **-d**, or **-l** options are specified.

  

     **-I**      Prevent **-A** from being automatically set for the super-user.  This option is not defined in IEEE Std 1003.1-2008 (“POSIX.1”).

  

     **-L**      Follow all symbolic links to final target and list the file or directory the link references rather than the link itself.  This option cancels the **-P** option.

  

     **-O**      Include the file flags in a long (**-l**) output.  This option is incompatible with IEEE Std 1003.1-2008 (“POSIX.1”).  See chflags(1) for a list of file flags and their

             meanings.

  

     **-P**      If argument is a symbolic link, list the link itself rather than the object the link references.  This option cancels the **-H** and **-L** options.

  

     **-R**      Recursively list subdirectories encountered.

  

     **-S**      Sort by size (largest file first) before sorting the operands in lexicographical order.

  

     **-T**      When printing in the long (**-l**) format, display complete time information for the file, including month, day, hour, minute, second, and year.  The **-D** option gives even

             more control over the output format.  This option is not defined in IEEE Std 1003.1-2008 (“POSIX.1”).

  

     **-U**      Use time when file was created for sorting or printing.  This option is not defined in IEEE Std 1003.1-2008 (“POSIX.1”).

  

     **-W**      Display whiteouts when scanning directories.  This option is not defined in IEEE Std 1003.1-2008 (“POSIX.1”).

  

     **-a**      Include directory entries whose names begin with a dot (‘.’).

  

     **-b**      As **-B**, but use C escape codes whenever possible.  This option is not defined in IEEE Std 1003.1-2008 (“POSIX.1”).

  

     **-c**      Use time when file status was last changed for sorting or printing.


---

### Key words:

---
#### TAGS


