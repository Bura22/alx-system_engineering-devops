#!/bin/bash
pwd: to print absolute path name
ls: to list the content of current directory
cd ~: to change the working directory to the user’s home directory
ls -l: to display current directory contents in a long format
ls -al: to display current directory contents, including hidden files (starting with .). Use the long format
ls -al: to display current directory contents in long format with user and group IDs displayed numerically and hidden files (starting with .)
mkdir /tmp/my_first_directory: to create a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory: to move th file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory/betty: to delete the file betty from my_first_directory
rm -rf /tmp/my_first_directory: to delete the directory my_first_directory
cd ..: to change the working directory to the previous one
ls -la .. /boot: to list all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile: to print the type of the file named iamafile
ln -s /bin/ls _ls_: to create a symbolic link to /bin/ls, named as  __ls__
cp -u *.html ..: to copy all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
