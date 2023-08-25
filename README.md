# MODBASH

Modifications of the behaviour of the bash command line, plus a few others

## Directory manipulation

### Making cd correct a filename into the directory it contains
`source modcorrectcd`

### Making cd use popd/pushd
`source modcorrectcd`

### nd: New directory and change to it
`source modnewdir`

## Command line

### Making tab-completion correct the case of a filename or directory
`source modtabcase`

## X server settings

### Make Ctrl-Alt-Backspace terminate the X server
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

## Python virtual environments

### Better virtual environment management

`source modvenv`

Defines a `venv` command.

Usage:

 `venv help|--help|-h`                  # show his help message

 `venv list`                            # list available virtual environments

 `venv activate ENVNAME`                # activate a virtual environment

 `venv create ENVNAME [PACKAGE ...]`    # create and activate a virtual environment

 `venv deactivate [ENVNAME]`            # deactivate a virtual environment
 
 `venv remove [ENVNAME]`                # remove a virtual environment

