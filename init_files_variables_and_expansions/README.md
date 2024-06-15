<h1 style="font-size: 48px; color: darkblue;"><b>Shell, init files, variables and expansions</b></h1>




[![Video explicativo](https://img.youtube.com/vi/AKSJOqn9pIY/0.jpg)](https://www.youtube.com/watch?v=AKSJOqn9pIY)

**************************************************************************
<h2 style="font-size: 48px><b> 1. Expansions</b></h2>
-------------------------------------------------------------------------
 ***-Pathname Expansion (Globbing):*** Uses wildcard characters like `*` and `?` to match filenames or paths (*.txt matches all .txt files).
 ***-Tilde Expansion:*** Refers to home directories using `~` (~/Documents expands to /home/username/Documents).
 ***-Variable Expansion:*** Substitutes variables with their values ($NAME where NAME=John becomes John).
 ***-Arithmetic Expansion:*** Performs arithmetic calculations within `((...))` or `$((...))` `(echo $((2 + 3)) expands to 5)` .
 ***-Command Substitution:*** Replaces the output of a command with the command itself using `...` or `$(...)` `(echo $(date) expands to the current date and time)` .
 ***-Brace Expansion:*** Generates strings by iterating through specified ranges or comma-separated values `{...}` `({apples,oranges} expands to apples oranges)` .

2.    Shell Arithmetic
3.    Variables
4.    Shell initialization files
5.    The alias Command
6.    Technical Writing
***************************************************************************

:rocket: **man or help :** `printenv` `set` `unset` `export` `alias` `unalias` `.` `source` `printf`


