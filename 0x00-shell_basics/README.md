0 pwd - script that prints the absolute path name of the current working directory.
1 ls - Display the contents list of your current directory.
2 cd - a script that changes the working directory to the user’s home directory.
3 ls -l - Display current directory contents in a long format
4 ls -l -a - Display current directory contents, including hidden files (starting with .). Use the long format.
5 ls -l -a -n - Display current directory contents.(Long format with user and group IDs displayed numerically And hidden files (starting with .)
6 mkdir /tmp/my\_first\_directory - Create a script that creates a directory named my\_first\_directory in the /tmp/ directory.
7 mv /tmp/betty /tmp/my\_first\_directory - Move the file betty from /tmp/ to /tmp/my\_first\_directory.
8 rm /tmp/my\_first\_directory/betty - Delete the file betty.
9 rm -r /tmp/my\_first\_directory - Delete the directory my\_first\_directory that is in the /tmp directory.
10 cd - - changes the working directory to the previous one.
11 ls -la . .. /boot - lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12 file /tmp/iamafile - script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13 ln -s /bin/ls __ls__ - symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14 cp -u *.html .. - script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
15 mv [[:upper:]]* /tmp/u - script that moves all files beginning with an uppercase letter to the directory /tmp/u
16 rm *~ -  script that deletes all files in the current working directory that end with the character ~
17 mkdir -p welcome/to/school - script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
18 ls -map - command that lists all the files and directories of the current directory, separated by commas (,).
Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line
19 Need to consult 

