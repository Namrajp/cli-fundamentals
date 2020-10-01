# cli-fundamentals
:computer: command line is fun. :+1: cli fundamentals is fun to learn. Here in code.

## Difference between Terminal and bash
Terminal is a user interface for typing commands. Bash is the program for running commands stored in the different paths.

## [Navigating in the terminal](./basic-commands.md)
`pwd` outputs present working directory, `whoami` prints current user.
## [Working with files and folders](./basic-commands.md)
`touch` create an new file.
`cp` copies a file ex.  `cp first.txt second.txt` -r flag is used to copy directory.
`mp` renames or moves a file ex.  `cp first.txt second.txt`
`mkdir` makes a directory
`cd` changes directory.
`rm` removes a files. `rm -rf some-dir` removes a directory.
[More Information](./basic-commands.md)

## [Help](./help.md) 
Help is verywhere whether it is stackoverflow or stackexchange or youtube. In docs it can be /Usr/share/docs/ and man and info pages are other sources of help.
[More Information](./help.md)


## [Permision, Ownership and Links](./permission.md)
Permission can enable or disable a user to open or read a file. If a file has no execute permission, it can not be run using ` $ ./file-name.txt`. And if a folder has no permission of write, it can not be opened. Users on a system can be three types, owner, group which is member of group, or  other. `chown` and `chgrp` are used to change group and owner.Root is member of sudo or wheel.
[More Information](./permission.md)


## [Environment Variables](./en-variables.md)
 Environment variables are group of system settings.`$ echo $PATH` shows path of programs like ls command.
 [More Information](./en-variables.md)


## [Find](./find-grep.md)
Used for finding files and folders, starts with find Path Expression, Expression can be wildcard exp or Regex exp E
[More Information](./find-grep.md)
## [Grep](./find-grep.md)
Used For finding strings in a single or multiple text files, also finds files in folders for a string value. Used with pipes,ps,cat, and ls etc.
[More Information](./find-grep.md)


## [Sed](./sed.md)
[More Information](./sed.md)


## System Information
[More Information](./systemInfo.md)

## [Lock Issues](./lockIssues.md)
[More Information](./lockIssues.md)


## [Markdowns](./markdown.md) 
Used for writing docs on the web, sometimes html file is written in markdown.
[More Information](./markdown.md)
