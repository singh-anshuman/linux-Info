# Linux Guide

## Important Commands

### File System Based

###### lsblk
Lists information about all or the specified block devices. The lsblk command reads the sysfs filesystem to gather information.

###### df -h
Checking disk usage in a human readable manner.

### File Management

###### cat > <FILE_NAME>
Creates a new file with the given file name.

###### cat fil

###### more <FILE_NAME>
Used for viewing the text file in terminal.

###### tail -f -n N <FILE_NAME>
Prints the last N number of lines of a given file. -f option continously prints last N files of the file. This option is frequently used to monitor live logs for an application.

###### ls -a
Lists all the files and directories including hidden files and directories.

###### ls -ltr
Lists all the files and directories on the current path in reverse cronological order of creation.

###### tar -zcvf file.tar.gz /path/to/dir/
Creates a tar file for the directory.

###### tar -C <FOLDER_PATH> -zxvf yourfile.tar.gz
Untars a tar.gz file to the specified directory.

###### tar -C <FOLDER_PATH> -xvf yourfile.tar
Untars a tar file to the specified directory.

###### which <EXECUTABLE_UTILITY>
Returns the path of the executable.

### User Management

###### sudo su -
Switches to root user and navigates to the root user's home directory.

## VI Editor Keyboard Shortcuts
###### q!
Quit without saving the file.

###### wq!
Quit after saving the changes.

###### w fileName
Write to file called fileName (save as).

###### w! fileName
Overwrite to file called fileName (save as forcefully).

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
