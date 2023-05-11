# Tips_and_Tricks
UNIX commands for beginners

# Useful websites to learn basix UNIX commands:

UNIX Tutorial for Beginners. http://www.ee.surrey.ac.uk/Teaching/Unix/index.html. 

# Commands:
[Access rights of files] (#access-rights-of-files)

## Access rights of files
Read this website for instructions: https://www.pluralsight.com/blog/it-ops/linux-file-permissions.

To list access rights of files, type ``ls -l``. 

An example of the result is ``-rwxrw-r-- 1 ee51ab beng95 2450 Sept29 11:52 file1``. 

## Environmental variable
It is global system variable accessible by all the processes/users running under the Operating System (OS), such as Windows, macOS and Linux. It is useful for storing system-wide values.

For example, we can use environmental variable to store directories. 

## Info server
Login to Info sever: type ``ssh username@info.mcmaster.ca``. Then type ``password`` (You don't see the characters when you enter the password). 

Exit Info server: type ``exit``.

## List (ls)
To list content in a directory, type ``ls``.

To list hidden files (files beginning with ``.``), type ``ls -a``. 

To list access rights of files, type ``ls -l``. 

## Working in background (nohup, screen)

## Symbolic link

Troubleshooting: 

- When changing the path for creating the symbolic link, remember to redo the symbolic link. 

## Tab complete
This saves time for typing out a command. 

For example, if you want to go to the **Applications** directory, you can type **"cd Applications"**. Instead of typing out **"Applications"** in full, you can type **"App"** and the press **"Tab"**. If **"Applications"** is the only directory beginning with **"App"**, it will return you **"cd Applications"**. 

