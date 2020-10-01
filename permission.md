# Permission
Permission for a file or folder can be seen using `ls -lah`
for example we have a .bashrc file with following :
`-rwxr-xr-x 1 nava staff 67B 2 Aug 2020 .bashrc`

The User nava is the owner and he is member of group staff. Other info is last updated on 2 Aug 2020, 67B file size. The first column is permission string which says owner has rwx, others and group has r-x ie read and execute permission.

## Change Permission
 ` $ chmod u+rwx go-x .bashrc`
 ` $ chmod 755 .bashrc` means 755 is octal notation where (7 is 111 binary ) ownder has rwx, group and others has 5 (5 is 101 binary ) means read and execute permission only.

 # Owner and Groups
 To change owner and groups we can use `chown` and `chgrp`. Root user has permission to change or delete any file. So change owner of file to root we can use `sudo`. Now, to remove a file with `rm .bashrc` we need root. Examples:
 `$ chown $USER:$GROUP .bashrc`
 `$ chgrp wheel .bashrc`
 `$ chown Root .bashrc`

 # Links
  Symlinks are used for soft links to a folder or files. While hard links are just like copy of file or folder.
  ` $ ln first-file.txt hard-link`
  `$ ln first.html my-link`