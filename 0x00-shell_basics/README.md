0-current_working_directory : prints the absolute path name of the current working directory.
ls :Display the contents list of your current directory
cd ~ : changes the working directory to the user’s home directory.
ls -l : Display current directory contents in a long format
ls -la :Display current directory contents, including hidden files (starting with .). Use the long format.
ls -lan: Display current directory contents.

    Long format
    with user and group IDs displayed numerically
    And hidden files (starting with .)
mkdir /tmp/my_first_directory: script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory/ :Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty - script deletes The file betty is in /tmp/my_first_directory
rmdir /tmp/my_first_directory - script Deletes the directory my_first_directory that is in the /tmp directory.
cd - changes the working directory to the previous one
 List all files in the current directory, including hidden files, in long format
ls -la . .. /boot : lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
ln -s /bin/ls __ls__ :Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory. 
find . -maxdepth 1 -type f -name '*.html' -newer ../ -exec cp -n {} .. \;: script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer thanthe versions in the parent of the working directory.

