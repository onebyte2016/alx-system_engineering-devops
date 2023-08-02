#!/bin/bash - Execute the file using the Bash shell
#pwd - print the current working directory
#ls - Display the contents list of my current directory
#cd ~ - Running this command will take you to your home directory, regardless of which directory you were previously in
#ls -l - List the content of the working directory in long format
#ls -la -Display current directory contents, including hidden files
#mkdir /tmp/6-firstdirectory -commad to creates a directory named my-first-directory in the /tmp/ directory.
#mv /tmp/betty /tmp/my_first_directory - to  ove a file from one folder to another within the same directory
#rm /tmp/my_first_directory/betty - used to delete the file betty from the directory tmp/my_first_directory
#rmdir /tmp/my_first_directory - to delete the directory in the tmp
#cd - -this command changes the working directory to the previous one.
#ls -la . .. /boot  - Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
#file /tmp/iamafile
#ln -s /bin/ls __ls__  -Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
#cp -un *.html .. - copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.You can consider that all HTML files have the extension .html
