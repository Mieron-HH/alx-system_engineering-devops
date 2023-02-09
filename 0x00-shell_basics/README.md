>>> 0-current_working_directory
	=> pwd
	- prints the absolute path name of the current working directory

>>> 1-listit
	=> ls
	- displays the contents list of your current directory

>>> 2-bring_me_home
	=> cd ~
	- changes the working directory to the user’s home directory

>>> 3-listfiles
	=> ls -l
	- displays current directory contents in a long format

>>> 4-listmorefiles
	=> ls -la
	- displays current directory contents, including hidden files (starting with i.)

>>> 5-listfilesdigitonly
	=> ls -lan
	- displays current directory contents in a long format with user and group IDs displayed numerically, including hidden files (starting with .)

>>> 6-firstdirectory
	=> mkdir tmp/my_first_directory
	-  creates a directory named my_first_directory in the /tmp/ directory

>>> 7-movethatfile
	=> mv /tmp/betty /tmp/my_first_directory/
	- moves the file betty from /tmp/ to /tmp/my_first_directory

>>> 8-firstdelete
	=> rm /tmp/my_first_directory/betty
	- deletes the file betty in /tmp/my_first_directory/ directory

>>> 9-firstdirdeletion
	=> rm -rf /tmp/my_first_directory
	- deletes the directory my_first_directory that is in the /tmp directory

>>> 10-back
	=> cd -
	- changes the working directory to the previous one

>>> 11-lists
	=> ls -al . ../ /boot
	- lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format

>>> 12-file_type
	=> file /tmp/iamafile
	- prints the type of the file named iamafile located in the /tmp directory

>>> 13-symbolic_link
	=> ln -s /bin/ls __ls__
	- create a symbolic link to /bin/ls, named __ls__

>>> 14-copy_html
	=> cp -u *.html ..
	- copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

>>> 100-lets_move
	=> mv *[A-Z]* /tmp/u
	- moves all files beginning with an uppercase letter to the directory /tmp/u

>>> 101-clean_emacs
	=> rm *~
	-  deletes all files in the current working directory that end with the character ~

>>> 102-tree
	=> mkdir -p welcome/to/school
	- creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory 
