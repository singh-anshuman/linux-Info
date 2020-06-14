# Linux Information

## Important Linux Commands

###### lsblk
Lists information about all or the specified block devices. The lsblk command reads the sysfs filesystem to gather information.

###### tail -f -n N <FILE_NAME>
Prints the last N number of lines of a given file. -f option continously prints last N files of the file. This option is frequently used to monitor live logs for an application.

###### sudo su -
Switches to root user and navigates to the root user's home directory.

###### ls -ltr
Listing all the files and directories in current directory in reverse cronological order.

###### ls -a
Listing all the files and directories including hidden files and directories.

###### tar -zcvf file.tar.gz /path/to/dir/
For creating a tar file for the directory

###### tar -C <FOLDER_PATH> -zxvf yourfile.tar.gz
For untarring a tar.gz file to the specified directory.

###### tar -C <FOLDER_PATH> -xvf yourfile.tar
Command for untarring a tar file to the specified directory

###### which <EXECUTABLE_UTILITY>
Command that gives you the path of the executable specified

## VI Editor Keyboard Shortcuts
###### q!
Quit without saving the file.

###### wq!
Quit after saving the changes.

###### :s/<search_string>
Searching a string in the file.

###### ctrl+d
Move forward half screen.

###### ctrl+f
Move forward full screen.

###### ctrl+u
Move backward half screen.

###### ctrl+b
Move backward full screen.

###### ctrl+e
Move screen up one line.

###### ctrl+y
Move screen down one line.

###### ctrl+I
Redraws screen.

**Note**: _These commands can be fired in command mode only. press _escape_ key to go into command mode._
