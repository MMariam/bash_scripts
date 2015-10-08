#bash_scripts

EXIT:
exit command exits the session while logging command history.
change_exit is a "script" that when ran, changes the function of the 
exit command and makes it save the history of all commands for the 
active terminal session in a log file with the name of the day the 
terminal session was exited.
#
change_exit: running this script is like an installation of the 
different exit command. After running this script, the exit command can 
be used and it will commit the additional functions before the terminal 
exits
#
running the exit script by itself, will perform it's additional 
functions and exit the terminal session. 

