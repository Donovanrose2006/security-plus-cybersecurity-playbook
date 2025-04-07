
| Command | Description | Flags |
| --- | --- | --- |
| ls | Lists entries in a directory | -a: List all entries <br/> -l: Long list <br/> -h: Human readable <br/> -R: Gives a recursive listing of the directory <br/> -s: Sorts by size <br/> -t: Sorts by time last modified
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
| cp | Copies a file | -v: Makes cp respond if successful <br/> -i: Prompts a user before overwriting a file <br/> -n: Does not let an overwrite happen <br/> -r: Lets cp copy both files and directories
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
