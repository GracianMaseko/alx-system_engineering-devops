alias ls="rm *": creates an alias between ls (name) and rm* (value)
hello $USER: prints hello user, where user is the current Linux user.
PATH=$PATH:/action: Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
$PATH | tr ":" "\n" | wc -l: counts the number of directories in the PATH.
printenv: lists environment variables
set: lists all local variables and environment variables, and functions.
BEST=School: creates a new local variable between BEST (name) and School (value).
echo $(($TRUEKNOWLEDGE+128)): prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $(($POWER/$DIVIDE)): prints the result of POWER divided by DIVIDE, followed by a new line.

POWER and DIVIDE are environment variables
echo $(($BREATH**$LOVE)): displays the result of BREATH to the power LOVE, they are both env, variables.
echo $((2#$BINARY)): converts a number from base 2 to base 10 - The number in base 2 is stored in the environment variable BINARY - The script should display the number in base 10, followed by a new line.
echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo: prints all possible combinations of two letters, except oo, Letters are lower cases, from a to z, One combination per line, The output should be alpha ordered, starting with aa, Do not print oo, script file should contain maximum 64 characters
printf "%x\n" $DECIMAL: prints a number with two decimal places, followed by a new line.
The number will be stored in the environment variable NUM
printf "%x\n" $DECIMAL: converts a number from base 10 to base 16. The number in base 10 is stored in the environment variable DECIMAL. The script should display the number in base 16, followed by a new line.
tr A-Za-z N-ZA-Mn-za-m: encodes and decodes text using the rot13 encryption. Assume ASCII. >> README.md

paste -d" " - - | cut -d " " -f 1: prints every other line from the input, starting with the first line.
export WATER=STIR: adds the two numbers stored in the environment variables WATER and STIR and prints the result.
