
-**List all Files that ends with a new line**  

`for file in *; do tail -c 1 "$file" | grep -q $'\n' && echo "$file"; done`  

-**This command is designed to prepend #!/bin/bash to the beginning of each file in the current directory and its subdirectories, excluding README.md**

`find . -type f ! -name 'README.md' -exec sh -c 'echo "#!/bin/bash" | cat - {} > temp && mv temp {}' \;`

-**This command appends a new line character to the end of each file found in the current directory and its subdirectories**

`find . -type f -exec sh -c 'echo "" >> "$1"' _ {} \;`

|**TASKS**|**FUNCTION|
|------------|------------|
|0. Hello World |Write a script that prints “Hello, World”, followed by a new line to the standard output.|
|1. Confused smiley |Write a script that displays a confused smiley "(Ôo)'.|
|2. Let's display a file|Display the content of the /etc/passwd file.|
|3. What about 2?|Display the content of /etc/passwd and /etc/hosts|
|4. Last lines of a file |Display the last 10 lines of /etc/passwd|
|5. I'd prefer the first ones actually |Display the first 10 lines of /etc/passwd|
|6. Line #2 |Write a script that displays the third line of the file iacta.
The file iacta will be in the working directory|
|7. It is a good file that cuts iron without making a noise|Write a shell script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text Best School ending by a new line.|
|8. Save current state of directory |Write a script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.|
|9. Duplicate last line |Write a script that duplicates the last line of the file `iacta` The file `iacta` will be in the working directory|
|10. No more javascript |Write a script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.|


