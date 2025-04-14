
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
