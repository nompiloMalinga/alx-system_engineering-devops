echo hello world - script printing hello world
echo "\"(Ôo)'" - Write a script that displays a confused smiley "(Ôo)'.
cat /etc/passwd - Display the content of the /etc/passwd file.
cat /etc/passwd  /etc/hosts -Display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd -Display the last 10 lines of /etc/passwd
head -n 10 /etc/passwd -Display the first 10 lines of /etc/passwd
head -n 3 | tail -n 1 - script that displays the third line of the file iacta.
echo"Best School"> \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) - script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
echo"Best School"> '\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)' - script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line..
ls -la >| ls_cwd_content -  script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
tail -n 1 iacta >> iacta -Write a script that duplicates the last line of the file iacta
find . -type f -name '*.js' -delete -script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d | wc -l - script that counts the number of directories and sub-directories in the current directory.

ls -lt | head -11 | tail -10 -  script that displays the 10 newest files in the current directory:
sort | uniq -u -script that takes a list of words as input and prints only words that appear exactly once.
grep -i "root" /etc/passwd -Display lines containing the pattern “root” from the file /etc/passwd
grep -c -i "bin" /etc/passwd -Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -A 3 -i "root" /etc/passwd -Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
grep -v -i "bin" /etc/passwd -Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
grep "^[[:alpha:]]" /etc/ssh/sshd_config -Display all lines of the file /etc/ssh/sshd_config starting with a letter.
tr "A" "Z" | tr "c" "e" -Replace all characters A and c from input to Z and e respectively.
tr -d "cC" -Create a script that removes all letters c and C from input.
