#Shell Scripting Basics Exercises

Exercise 0: pwd === print working directory

Exercise 1: ls === list directory contents

Exercise 2: cd === change directory.

Exercise 3: ls -l === list directory contents in long form

Exercise 4: ls -la === list directory contents in long form, including hidden files

Exercise 5: ls -al === list file digits only

Exercise 6: mkdir /tmp/my_first_directory Create my first directory inside the tmp directory

Exercise 7: mv /tmp/betty -t /tmp/my_first_directory/betty === Move file betty, which is located inside the tmp directory, to my first directory, which is also located inside the tmp directory.

Exercise 8: rm /tmp/my_first_directory/betty === Remove file betty located in tmp/my_first_directory directory.

Exercise 9: rmdir /tmp/my_first_directory === Remove directory my first_directory located in directory tmp.

Exercise 10: cd - === Change directory to the previous directory you were in.

Exercise 11: ls -la . .. /boot === List all files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of working directory, and /boot directory. The ls command allows multiple directories to be listed separated by spaces.

Exercise 12: file /tmp/iamafile === Prints the type of file iamafile.

Exercise 13: ln -s /bin/ls __ls__ === Create a symbolic link named ls for /bin/ls

Exercise 14: cp -u *.html --parents /tmpp == Copy all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory (-u option). 

Exercise 15: mv [[:upper:]]* -t /tmp/u === Move all files that begin with a capital letter to /tmp/u

Exercise 16: rm *~  === Deletes all files in the current directory that end with a ~

Exercise 17: mkdir -p welcome/to/school === Create directory welcome in current directory. Create directory to inside directory welcome. Create directory school inside directory to. The -p option creates any intermediate directories in the path argument.

Exercise 18: ls -xamp === List all files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

Exercise 19: 0 string SCHOOL School data !:mime School Create a magic file called school.mgc that can be used with the command file to detect School data files. Holberton data files always contain "SCHOOL" at offset 0.
