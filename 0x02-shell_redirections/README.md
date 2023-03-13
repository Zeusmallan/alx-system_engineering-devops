echo " " prints a data or text on the standard output.
echo "(Ôo)" script that displays a confused smiley.
cat Display the content of a file.
cat can also be used to display the contents of multiple files.
ls | head /etc/passwd Display the first 10 lines of /etc/passwd.
ls | head -3 iacta | tail +3  script that displays the third line of the file iacta.
tail -1 iacta >> iacta  script that duplicates the last line of the file iacta
find . -type f -name '*.js' -delete script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
ls -t . | head Create a script that displays the 10 newest files in the current directory.
sort | uniq -u Create a script that takes a list of words as input and prints only words that appear exactly once
grep "bin*" /etc/passwd | wc -l Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -A 3 "root" /etc/passwd Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
grep -L "bin" /etc/passwd Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
grep ^'[[:aplpha:]]' /etc/ssh/sshd_config Display all lines of the file /etc/ssh/sshd_config starting with a letter.
tr 'Ac' 'Ze' Replace all characters A and c from input to Z and e respectively.
tr -d 'Cc' Create a script that removes all letters c and C from input
rev script that reverse its input.
cut -d ':'-f  1, 6 /etc/passwd | sort script that displays all users and their home directories, sorted by users.
find . -empty | rev | cut -d '/' -f 1 | rev  script that displays all users and their home directories, sorted by users.
find . -type f -name "*.gif* | rex | cut -d "/" -f 1 | cut -d '.' 2- |rev| LC_AL
L=C sort .f script that lists all the files with a .gif extension in the current directory and all its sub-directories
