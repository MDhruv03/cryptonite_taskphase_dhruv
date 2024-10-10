# cat
simple cat command to read a file
# catting absolute paths
cat command with an absolute path to read a file
# catting more practice
path for flag is provided upon opening the terminal and then simple cat
# grepping for a needle in a haystack
grep command to look for specific content in big files
# listing files
ls command lists files
# touching files
touch command creates files
# removing files
rm commands removes files
# hidden files
ls -a command lists all the files that ls may overlook
# epic file quest game
Longest challenge by far.Had to ls through a bunch of paths and then cat from one file to another in order to find the flag.
# making directories
mkdir command makes directories
# Finding files
slightly long challenge which required us to use the find command, to find the flag I first did "find / -name flag" this listed alot of directories ending in flag, I started to cd into each hoping to the flag until one responded back as "this is not a directory", I simply use cat command on this file and found the flag.
# linking files
In this challenge we learn to use ln -s command to link files. the /catflag is linked to /not-the-flag so here I used the ln -s command to link not-the-flag to /flag so when /catflag is used we end up reading from /flag as intended as its given the flag is inside /flag.
