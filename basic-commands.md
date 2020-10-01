# Basic Commands

## Navigating in the terminal
`pwd` outputs present working directory, `whoami` prints current user.
## Working with files and folders
`touch` create an new file.
`cp` copies a file ex.  `cp first.txt second.txt` -r flag is used to copy directory.
`mp` renames or moves a file ex.  `cp first.txt second.txt`
`mkdir` makes a directory
`cd` changes directory.
`rm` removes a files. `rm -rf some-dir` removes a directory.

## Creating file and folders
`Touch newFile.txt someFile.css thirdFile.js` creates three files 
## Head List 
`head -n 10` few lines from top 
## tail List 
`tail -n 10`  few lines from bottom
## less
less is used to read file in a program similar to vim. CTRL U/D/B can be used for navigation, q quit.
## cat
cat is used to concatenate files and read
`cat first.txt second.txt` Outputs concatenation

## WC 
WC stands for Word Count, it can take flags -l number of lines, -w no. of words, c for no. of bytes.

## Redirection
### >   
is used to redirect output to standard output or stdout for short. ex. ` echo "Hello World" > someFile.txt`
## >>
 is used to append output to stdout
` echo "My name is Nava" >> someFile.txt`
## 2> stderr
## &> std out plus stderr

[Cli fundamentals](https://github.com/Namrajp/cli-fundamentals)
