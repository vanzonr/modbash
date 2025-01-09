# MODBASH

Modifications of the behaviour of the bash command line, plus a few others

## Directory manipulation

### Making cd correct a filename into the directory it contains and use pop/pushd
`source modcorrectcd`

### nd: New directory and change to it
`source modnewdir`

## Command line

### Making tab-completion correct the case of a filename or directory
`source modtabcase`

### bash prompt with date, time, loaded environment modules and git branch
`source modprompt`

## X server settings

### Make Ctrl-Alt-Backspace terminate the X server (X11 only)
`source modctrlaltbksp`

## Git

### Better git and additional git-related commands

`source modgit`

Redefines `git` command to always mark a directory as safe before
proceeding with the actual git command

Furthermore defines:

`gitwsup`: give summary of the branch and tracked files

`gitwhich`: finds the .git directory

`gitmksafe` marks the repo safe.

