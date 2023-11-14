# Linux shell basics

Let's dive into some basic Linux shell commands.

**ls - List Files**:

The ls command is used to list the files and directories in the current directory.

Example:

```
ls
```

**cd - Change Directory**:

The cd command is used to change the current working directory.

Example:

cd Documents

**pwd - Print Working Directory**:

The pwd command prints the current working directory.

Example:

```
Pwd
```

**cp – Copy**:

The cp command is used to copy files or directories.

Example:

```
cp file.txt backup/
```


**mv - Move/Rename**:

The mv command is used to move or rename files or directories.

Example:

```
mv file.txt new_location/
```

**rm - Remove/Delete**:

The rm command is used to remove or delete files and directories.

Example:

```
rm unwanted_file.txt
```

**mkdir - Make Directory**:

The mkdir command is used to create a new directory.

Example:

```
mkdir new_directory
```

**rmdir - Remove Directory**:

The rmdir command is used to remove an empty directory.

Example:

```
rmdir empty_directory
```

**cat - Concatenate and Display**:

The cat command is used to display the contents of a file.

Example:

```
cat file.txt
```

**echo - Display Text**:

The echo command is used to display text on the terminal.

Example:

```
echo "Hello, Linux!"
```

**touch - Create Empty File**:

The touch command is used to create an empty file.

Example:

```
touch new_file.txt
```

**nano - Text Editor**:

The nano command opens a simple text editor.

Example:

```
nano new_file.txt
```

Press Ctrl + X to exit, and it will prompt you to save changes.

**grep - Search Text**:

The grep command is used to search for a specific pattern in a file.

Example:

```
grep "keyword" file.txt
```

**chmod - Change Permissions**:

The chmod command is used to change the permissions of a file or directory.

Example:

```
chmod +x script.sh
```

This makes the script executable.

**ps - Process Status**:

The ps command displays information about running processes.

Example:

```
ps aux
```

**kill - Terminate Process**:

The kill command is used to terminate a process.

Example:

```
kill PID
```

Replace PID with the actual process ID.

**df - Disk Free**:

The df command shows the amount of disk space available on the file system.

Example:

```
df -h
```

The -h option makes the output human-readable.

**du - Disk Usage**:

The du command displays the disk usage of files and directories.

Example:

```
du -sh directory_name
```

**tar - Tape Archive**:

The tar command is used to compress and archive files.

Example (create a tarball):

```
tar -czvf archive.tar.gz directory_to_compress/
```

**wget - Download from the Web**:

The wget command is used to download files from the internet.

Example:

```
wget https://example.com/file.zip
```

**df - Display Free Disk Space**:

The df command without any options displays free disk space for all mounted filesystems.

Example:

```
df
```

**free - Display Free Memory**:

The free command shows the amount of free and used memory in the system.

Example:

```
free -h
```

The -h option makes the output human-readable.

**ps - Display Process Status**:

The ps command with various options can display detailed information about processes.

Example:

```
ps aux | grep process_name
```

Replace process_name with the actual name of the process.

**history - Command History**:

The history command shows a list of previously executed commands.

Example:

```
history
```

You can also use !n to execute the command with number n from history.

**man - Manual Pages**:

The man command displays the manual or help pages for a given command.

Example:

```
man ls
```

Use arrow keys to navigate, and press q to exit.

**find - Search for Files**:

The find command is used to search for files and directories based on various criteria.

Example:

```
find /path/to/search -name "*.txt"
```

This finds all files with a .txt extension.

**grep - Search Text in Files**:

The grep command can search for a specific pattern in files.

Example:

```
grep "pattern" file.txt
```

**awk - Text Processing**:

The awk command is a powerful text processing tool.

Example:

```
cat file.txt | awk '{print $2}'
```

This prints the second column of a space-separated file.

**sed - Stream Editor**:

The sed command is used for text stream processing.

Example:

```
cat file.txt | sed 's/old/new/g'
```

This replaces all occurrences of 'old' with 'new' in the file.

**alias - Create Command Aliases**:

The alias command is used to create aliases for other commands.

Example:

```
alias ll='ls -la'
```

Now you can use ll instead of ls -la.




