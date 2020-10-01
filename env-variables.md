# Environment Variables
 Environment variables are group of system settings. Typing
`env` reveals list of variables and values, capital letters on environment variables.
`$ echo $PATH`

## To create env variables:
`$ export projDir=/Usr/namraj/sites`
`cd $projDir`  we have to use $ to use env variables
`echo $projDir` 

## Save permanently 
To save permanently in bash,we need to write it inside config
file,configuration file for bash is
.bashprofile, in ohmyzsh .zshrc file.