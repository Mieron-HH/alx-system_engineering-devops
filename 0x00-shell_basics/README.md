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
