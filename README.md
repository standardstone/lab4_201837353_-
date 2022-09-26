### pwd: shows the current path in a hierarchical directory 

### cd: change directory

### ls: list files and directories
#### More on ls

```sh
ls /bin List diles in the /bin directory (or any other directory we care to sperify)
ls -l List the files in the working directory in long format
ls -l /etc/bin List the files in the /bin directory and the /etc directory in long format
ls -la .. List all files
```
### Shell command: clear
### cp: copy files and directories
#### More on  cp
```sh
cp file1 file2 copies the contents of file1 into file2. If file2 does not exist, it is created; otherwise, file2 is silently overwritten with the contents of file1.
cp -i file1 file2 Like above however,since the "-i"(interactive) option is sepcified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
cp file1 dir1 Copy the contents of file1 (into a file names file1)inside of directory dir1
cp -R dir1 dir2 Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory names dir1 within directory dir2.
```
### mv: move files and directories or rename them
rm: delete files and directories
mkdir: make a new directory
Manipulation: Wildcards
Help command: help,men
exit
