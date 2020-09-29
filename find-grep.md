# Find 
**Syntax:** filepath expression  
__Usage__ Find is used to find files or folders. Example,

## Examples
`find downloads`  if you are in ~ or home folder then it outputs list of files in downloads

`find /etc/ -name "resolv.conf"`   
`find . -name "*.???"` ? is for single char so any files with three ext. 
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