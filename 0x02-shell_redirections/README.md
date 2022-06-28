echo: prints “Hello, World”, followed by a new line to the standard output
echo \"\(Ôo\)\': script that displays a confused smiley "(Ôo)'
cat /etc/passwd: Display the content of the /etc/passwd file
cat /etc/passwd /etc/hosts: Display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd: Display the last 10 lines of /etc/passwd
head -n 10 /etc/passwd: Display the first 10 lines of /etc/passwd 
head -n 3 iacta | tail -n 1: displays the third line of the file iacta
echo "Best School" | cat > '\*\\'\''\*\\'"Best School"\'\\*$\?\*\*\*\*\*:): reates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
ls -la > ls_cwd_content: writes into the file ls_cwd_content the result of the command ls -la
tail -n 1 iacta | cat >> iacta: duplicates the last line of the file iacta
find . -name "*.js" -type f -delete: deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -mindepth 1 -type d | wc -l: counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted
ls -t | head: displays the 10 newest files in the current directory.
sort | uniq -u: takes a list of words as input and prints only words that appear exactly once
grep root /etc/passwd: Display lines containing the pattern “root” from the file /etc/passwd
grep -c bin /etc/passwd: Display the number of lines that contain the pattern “bin” in the file /etc/passwd
cat /etc/passwd | grep -A 3 "root": Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
grep -v bin /etc/passwd: Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
grep ^[[:alpha:]]  /etc/ssh/sshd_config: Display all lines of the file /etc/ssh/sshd_config starting with a letter.
