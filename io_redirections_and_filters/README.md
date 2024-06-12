|||
|------------|------------|
|**List all Files that ends with a new line**|`or file in *; do tail -c 1 "$file" | grep -q $'\n' && echo "$file"; done`|
|**This command is designed to prepend #!/bin/bash to the beginning of each file in the current directory and its subdirectories, excluding README.md**|`find . -type f ! -name 'README.md' -exec sh -c 'echo "#!/bin/bash" | cat - {} > temp && mv temp {}' \;`|
|**This command appends a newline character to the end of each file found in the current directory and its subdirectories**|`find . -type f -exec sh -c 'echo "" >> "$1"' _ {} \;`|

