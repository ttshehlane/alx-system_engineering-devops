0) alias ls='rm *'  | creates an alias name ls of value rm *
1) echo "hello $USER"  | prints hello user, where user is the current Linux user.
2) PATH=$PATH:/action  | Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
3) echo $PATH | tr ":" "\n" | wc -l  | counts the number of directories in the PATH.
4) printenv  | lists environment variables.
5) set  | lists all local variables and environment variables, and functions.
6) BEST="School"  | creates a new local variable BEST value School
7) export BEST="School"  | creates a new global variable BEST value School
8) echo $(($TRUEKNOWLEDGE+128))  | prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
9) echo $(($POWER/$DIVIDE))  | prints the result of POWER divided by DIVIDE, followed by a new line.(POWER and DIVIDE are environment variables)
10) echo $(($BREATH**$LOVE))  | displays the result of BREATH to the power LOVE (BREATH and LOVE are environment variables. The script should display the result, followed by a new line)
11) echo $((2#$BINARY))  | converts a number from base 2 to base 10. (The number in base 2 is stored in the environment variable BINARY. The script should display the number in base 10, followed by a new line)
12) echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo  | prints all possible combinations of two letters, except oo (Letters are lower cases, from a to z. One combination per line. The output should be alpha ordered, starting with aa. Do not print oo.
13) printf "%0.2f\n" $NUM  | prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.
14) printf "%x\n" $DECIMAL  | converts a number from base 10 to base 16. (The number in base 10 is stored in the environment variable DECIMAL. The script should display the number in base 16, followed by a new line)
15) tr '[A-Za-z]' '[N-ZA-Mn-za-m]'  | encodes and decodes text using the rot13 encryption. Assume ASCII.
16) paste - - | cut -f1  | prints every other line from the input, starting with the first line.
17) printf "%o\n" "$((5#$(echo $WATER | tr 'water' '01234')+5#$(echo $STIR | tr 'stir.' '01234')))" | tr '01234567' 'bestchol'  | adds the two numbers stored in the environment variables WATER and STIR and prints the result. WATER is in base water. STIR is in base stir. The result should be in base bestchol

