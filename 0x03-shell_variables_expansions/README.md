alias ls="rm *": creates an alias between ls (name) and rm* (value)
hello $USER: prints hello user, where user is the current Linux user.
PATH=$PATH:/action: Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
$PATH | tr ":" "\n" | wc -l: counts the number of directories in the PATH.
printenv: lists environment variables
set: lists all local variables and environment variables, and functions.
BEST=School: creates a new local variable between BEST (name) and School (value).
echo $(($TRUEKNOWLEDGE+128)): prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
