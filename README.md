# cli-fundamentals
:computer: command line is fun. :+1: cli fundamentals is fun to learn. Here in code.

## Difference between Terminal and bash
Terminal is a user interface for typing commands. Bash is the program for running commands stored in the different paths.

## Navigating in the terminal
`pwd` outputs present working directory, `whoami` prints current user.
## Working with files and folders
`touch` create an new file.
`cp` copies a file ex.  `cp first.txt second.txt` -r flag is used to copy directory.
`mp` renames or moves a file ex.  `cp first.txt second.txt`
`mkdir` makes a directory
`cd` changes directory.
`rm` removes a files. `rm -rf some-dir` removes a directory.

# Find 
**Syntax:** filepath expression  
__Usage__ Find is used to find files or folders. Example,

## Examples
`find downloads`  if you are in ~ or home folder then it outputs list of files in downloads

`find /etc/ -name "resolv.conf"`   
`find . -name "*.???"` ? is for single char so any files with three text. 
`find . -name "*main*"` finds any files with word main within

`find . -name "first.txt"`  
`find . -name "[fts]*"` files with any of characters fts.

# Grep 
**Syntax** expression file/filepath
__Usage__ grep is used to find specific string or text file

## Examples

`grep -r eth0 /etc/*`  
`grep eth[01] /etc/*`  
`grep -E "127.*(twain\.example\.com|localhost)"`

`grep -i "elie" names.txt`  
`ps ax | grep xterm`