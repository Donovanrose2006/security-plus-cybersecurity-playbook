
| Command | Description | Flags |
| --- | --- | --- |
| ls | Lists entries in a directory | -a: List all entries <br/> -l: Long list <br/> -h: Human readable <br/> -R: Gives a recursive listing of the directory <br/> -s: Sorts by size <br/> -t: Sorts by time last modified <br/> -d: Prevents files from subdirectories from being displayed
| whoami | Gives the username of the user |
| uname | Gives the current kernal used | -n: Gives the network node hostname
| pwd | Gives the current directory in use | 
| echo | Repeats what is typed after the command | $: Echos a certain variable or path instead 
| history | Gives the last used commands, default 10 | {Number}: Sets the amount of previous commands shown <br/> !: Repeats the command used in order of history
| which | Finds an executable file with the text entered | 
| type | Gives the source of a command | -a: Gives all locations that contain the command
| alias | Gives aliases on the current shell | 
| man | Gives the manual for a specified command | -k: Searches for a keyword inside a manual <br/> -f: See all manual pages for a keyword
| apropos | *see man -k* |
| whatis | *see man -f* |
| info | Gives an easy to read lesson on a command |
| locate | Finds a file |
| cp | Copies a file | -v: Makes cp respond if successful <br/> -i: Prompts a user before overwriting a file <br/> -n: Does not let an overwrite happen <br/> -r: Lets cp copy both files and directories <br/> -p: Preserves the original timestamp on the copy
| cat | Lets you see the contents of a file 
| mv | Moves a file | *(Same as cp except -r)*
| touch | Creates an empty file |
| rm | Deletes a file | -i: Gives a prompt before deleting a file <br/> -r: Allows the deletion of a directory
| rmdir | Removes a directory (If it is empty) |
| mkdir | Creates a directory |
| gzip | A common compression application for Linux | -d: Returns the file to it's original size
| tar | Turns multiple files into a single output (archiving), much like compression | -c: Creates an archive <br/> -f: Use the archived file <br/> -z: Compresses/Decompresses the file <br/> -t: Lists the files in an archive <br/> -x: Extracts files from an archive <br/> -v: Lists all the files processed
| zip | Archives using Microsoft's .zip format | 
| unzip | Unarchives .zip files |
| head/tail | Shows the first/last few lines in a file | -5: Shows 5 lines <br/> -n: Shows the last specified amount of lines in Unix, Shows everything but specified in GNU, unless number is prefixed with +
| sort | Rearranges the order of files or input | -t: Allows another field seperator to be specified <br/> -k#: Specifies the field number <br/> -n: Numeric sort <br/> -r: Reverse sort 
| wc | Specifies the amount of bytes, words, and lines in a file | -l: Only specifies the number of lines <br/> -w: Only specifies the number of words <br/> -c: Only specifies the amount of bytes
| cut | Extracts columns from a text file | -d: Specifies alternate delimiters <br/> -f: Specifies which fields to display <br/> -c: Bases extraction on character position
| grep | Used to filter lines in a file or outputs of another command | --color: Colors specified word in red <br/> -c: Provides a count of how many lines match <br/> -n: Displays original line numbers <br/> -v: Inverts the search, searching for files that does NOT include the search <br/> -i: Ignores case <br/> -w: Only returns lines that contain full word matches
| ascii | Shows the ASCII table | 
| test | Used for easy comparison of strings (Left bracket can also be used) | -f: File test <br/> -d: Directory test <br/> -eq: Numeral comparison <br/> -o: Or <br/> -a: And
| arch | Shows the family the current CPU belongs to
| lscpu | Gives more information about the current CPU
| free | Shows the amount of RAM on the system | -m: Rounds to the nearest megabyte <br/> -g: Rounds to the nearest gigabyte <br/> -s #: Specifies how often to update (in seconds)
| lsusb | Shows the USB devices connected to the system
| fdisk | Can be used to show partition information | 
| umount | Unmounts an optical drive
| ps | Shows current processes | --forest: Shows parent and child relationships between commands <br/> -ef: Shows all processes on the system <br/> -u: Shows the processes of a specific user
| top | Shows a regularly updating interface of processes, sorted by CPU usage | 
| kill | Allows the user to terminate a process of their choice
| vi | Opens the vi text editor 
| chmod | Changes the permissions on a file
| sysctl | Gives attributes of the current kernal
| jobs | Shows currently running commands
| syslogd | Shows system logs
| host | Gives the IP address a domain name is associated with, or vice versa | CNAME: Checks if there is a Canonical Name for the address | SOA: Start of Autority, indicates the primary server for the domain | -a: All
| ifconfig | Displays network configuration information...slowly becoming obsolete
| ip | A command with increased functionality and more options than ifconfig, somewhat of an umbrella command for more obsolete commands
| route | Gives a table that describes where network packages are sent...being replaced by ip route (show)| -n: Gives numeric data only 
| ping | Used to determine if a machine is reachable, sends packets to a specified IP to check
| netstat | Powerful command that provides large amount of network information | -r: Displays routing information <br/> -t: Specifically TCP protocols <br/> -l: Shows which ports are listening <br/> -n: Shows numbers, not names
| ss | Shows socket statistics, supports all major packet and socket types | -s: Gives a summary of types of sockets and statistics about them
| dig | Performs queries on a DNS server to determine if needed information is available on the server
| ssh | Allows remote machine connections
| exit | Exits the virtual machine environment, terminal itself, or any seperate command
| sudo | Allows a user to execute administrator commands (instead of the using the root account)
| su | Switches an account to other users or the root account | -l: Gives a prompt to fully log in, instead of only changing the UID
| getent | Like grep, but can access local account information, or info on a network directory server
| id | Prints user or group information about a specific user | -g: Prints a users primary group <br/> -G: Used to verify a users secondary group memberships
| who | Displays a list of users currently logged into the system | -b: Shows the last time the system was booted <br/> -r: Shows the time the system reached the current run level 
| w | Shows a more detailed version of the who command 
| last | Displays all login and boot records
| groupadd | Executed by the root user to create a new group | -g: Used to specify a group ID for the new group (or change the ID of an old one) <br/> -r: Assigns the group a new ID that is less than the lowest standard GID <br/> -n: Changes the name of the specified group 
| groupdel | Deletes the specified group
| useradd | Adds a user profile | -D: Allows you to view or change the default values used by useradd <br/> -g: Allows you to use a different primary group <br/> -b: Allows you to use a different base directory <br/> -f: Allows you to use a different INACTIVE value <br/> -e: Allows you to use a different EXPIRE value <br/> -s: Allows you to use a different login shell <br/> -k: Allows you to use a different SKEL directory <br/> -u: Allows you to specify a UID <br/> -G: Allows you to specify supplementary groups <br/> -M: Tells the command to not create a new home directory <br/> -m: Makes a new directory <br/> -d: Allows you to create or specify a home directory for a new user <br/> -c: Adds a comment, typically a users full name
| passwd | Allows a password change
| chage | Provides options for managing passwords | -l: Lists the account aging information <br/> -d: Sets the date of last password change <br/> -E: Sets account to expire on specified date <br/> -I: Sets account to permit login for specified days after password expires <br/> -m: Sets minimum days for password change <br/> -M: Sets maximum days before a password will change <br/> -W: Sets amount of days until user should be warned to change their password
