|./ File name|DESCRIPTION      |
|------------|------------|
|**0. My name is Betty**|switches the current user to the user `betty`.|
|**1. Who am i**|prints the effective username of the current user|
|**2. Groups**|prints all the groups the current user is part of.|
|**3. New owner**|script that changes the owner of the file `hello` to the user `betty`.|
|**4. Empty!**|script that creates an empty file called `hello`|
|**5. Execute**|script that adds execute permission to the owner of the file `hello`|
|**6. Multiple permissions**|script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`|
|**7. Everybody!**|script that adds execution permission to the owner, the group owner and the other users, to the file `hello`|
|**8. James Bond**|script that sets the permission to the file `hello` as follows:|

    .Owner: no permission at all
    .Group: no permission at all
    .Other users: all the permissions
|./ File name|DESCRIPTION|
|------------|------------| 
|**9. John Doe**|script that sets the mode of the file hello to this:`-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`|
|**10. Look in the mirror**|script that sets the mode of the file `hello` the same as `olleh’s` mode.|
|**11. Directories**|script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.|
|**12. More directories**|script that creates a directory called `my_dir` with permissions 751 in the working directory.|
|**13. Change group**|script that changes the group owner to `school` for the file `hello`|
|**14. Owner and Group**|script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.|
|**15. Symbolic links**|script that changes the owner and the group owner of `hello` to vincent and staff respectively.|
|**16. If only**|script that changes the owner of the file `hello` to vincent only if it is owned by the user guillaume.|



