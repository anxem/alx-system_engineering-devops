## 0x01. Shell, Permissions

[0-iam_betty](./0-iam_betty) - Create a script that switches the current user to betty. You should use exactly 8 character for your command (+1 character for the new line). You can assume that the user betty will exist when we run your script.

[1-who_am_i](./1-who_am_i) - Write a script that prints the effective username of the user.

[2-groups](./2-groups) - write a script that prints all the group the current user is part of.

[3-new_owner](./3-new_owner) - Write a script that change the owner of the file hello to the user betty.

[4-empty](./4-empty) - Write a script that create an empty file called hello.

[5-execute](./5-execute) - Write a script that adds execute permission to the owner of the file hello. The file hello will be in the working directory.

[6-multiple_permissions](./6-multiple_permission) - Write a script that add execute permission to the owner and the group owner and read permission to other user to the file hello. The file hello will be in the working directory

[7-everybody](./7-everybody) - Write a script that add execution permission to the owner, the group owner and the other user to the file hello. The file hello will be in the working directory. You are not allowed to use commas for this script.

[8-James_Bond](./8-James_Bond) - Write a script that set permission the the file as follows:
- Owner: No permission at all
- Group: No permission at all
- Other User: All permission.
The file hello will be in the working directory and you are not allow to use commas for thsi script.

[9-John_Doe](./9-John_Doe) - Write a script that set the mode of the file hello to this:
```sh

-rwxr-x-wx 1 Julien Julien  23 sep 20 14:25 hello

```
- The file hello will be in the working directory
- You are not allowed to use commas for this script.

[10-mirror_permissions](./10-mirror_permissions) - Write a script that set the mode of th file hello to the same as olleh's mode.
- The file hello will be in the working directory
- The file olleh will be in the working directory.

[11-directories_permissions](./11-directories_permissions) - Create a script that adds execute permission to all subdirectoriesof the current directory of the owner, the group and all other user. Regular files should not be changed.

[12-directory_permissions](./12-directory_permissions) - Create ascript that create a directory called my_dir with permissions 751 in the working directory.

[13-change_group](./13-change_group) - Write a script that change the group owner to School from file hello
- The file hello will be in the working directory.

[100-change_owner_and_group](./100-change_owner_and_group) - Write a script that change the owner to vincent and the group owner to staff for all file and directory i9n the working directory.

[101-symbolic_link_permissions](./101-symbolic_link_permission) - Write a script that change the owner and group owner of _hello to vincent and staff respectively.
- The file _hello is in the working directory
- The file _helo is a symbolic link

[102-if_only](./102-if_only) - Write a script that changes the owner of the file hello to betty only if it sis owned by the user guillaume.
- The file hello will be in the working directory

[103-Star_Wars](./103-Star_Wars) - Write a script that will play star War IV episode in the terminal.