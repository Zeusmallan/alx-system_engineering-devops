pwd A script that prints the absolute path name of the current working directory
ls Display the contents list of your current directory
cd ~ A script that changes the working directory to the user’s home directory
ls -l Display current directory contents in a long format
ls -la Display current directory contents, including hidden files (starting with .). Use the long format
ls -la Display current directory contents
mkdir A script that creates a directory
mv Move the file
rm Delete the file
rmdir Delete the directory
cd ..A script that changes the working directory to the previous one
ls -al . .. /boot A script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
file /tmp/iamfile A script that prints the type of the file named iamafile
ln -s /bin/ls __ls__ Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory
cp -un *.html ../ A script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
mv [[:upper:]]* /tmp/u A  script that moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~ Script that deletes all files in the current working directory that end with the character ~.
