## Bandit Over The Wire - [LINUX BASICS]


## Level - 0

1. Logged in to the Bandit0 server using the command 'ssh bandit0@bandit.labs.overthewire.org -p 2220' using the password 'bandit0' given in the website.
 
## Level 0 -> 1

1. Logged in to the Bandit0 server using the command 'ssh bandit0@bandit.labs.overthewire.org -p 2220' using the password 'bandit0' given in the website.

2. It was given that the password for the next levelwas stored in a readme file.

3. Searched for the readme file using 'ls' command.

4. Opened the readme file using the command 'cat readme'.

5. The password 'NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL' was displayed.

## Level 1 -> 2
1. Logged in to the Bandit1 server using the command 'ssh bandit1@bandit.labs.overthewire.org -p 2220' using the password 'NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL' given in the previous level.

2. It w given that the password for the next level is stored in a file called - located in the home directory.

3. Searched for the - file using 'ls' command.

4. Opened the - file using the command 'cat ./-'

5. The password 'rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi' was displayed.
   
## Level 2 -> 3

1. Logged in to the Bandit2 server using the command 'ssh bandit2@bandit.labs.overthewire.org -p 2220' using the password 'rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi' given in the previous level.

2. It was given that the password for the next level is stored in a file called spaces in this filename located in the home directory.

3. Searched for file called 'spaces in this filename' using 'ls' command.

4. Opened the file using the command "cat 'spaces in this filename'".

5. The password 'aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG' was displayed.
   

## Level 3 -> 4

1. Logged in to the Bandit3 server using the command 'ssh bandit3@bandit.labs.overthewire.org -p 2220' using the password 'aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG' given in the previous level.

2. It was given that the password for the next level is stored in a hidden file in the inhere directory.

3. Opened the inhere directory by using the command 'cd inhere'.

4. Searched for hiiden files by using the command 'ls -a'

5. Opened the hiiden file by using the command 'cat .hidden'

6. The password '2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe' was displayed.

## Level 4 -> 5

1. Logged in to the Bandit4 server using the command 'ssh bandit4@bandit.labs.overthewire.org -p 2220' using the password '2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe' given in the previous level.

2. It was given that the password for the next level is stored in the only human-readable file in the inhere directory.

3. Opened the inhere directory by using the command 'cd inhere'.

4. Searched for human readable files by using the command 'ls -la'

5. Opened the file './-file07' which contained ASCII text by using 'cat ./-file07'

6. The password 'lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR' was displayed.
   
## Level 5 -> 6

1. Logged in to the Bandit5 server using the command 'ssh bandit5@bandit.labs.overthewire.org -p 2220' using the password 'lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR' given in the previous level.

2. It was given that the password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
    human-readable
    1033 bytes in size
    not executable
3. Opened the inhere directory by using the command 'cd inhere'.

4. Searched for the file with gven specifications using the command 'find . -type f -size 1033c ! -executable -exec file '{}' \; | grep ASCII'.

5. Opened the fiel using the command 'cat ./maybehere07/.file2'.

6. The password 'P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU' was displayed.

## Level - 7
## Level - 8
## Level - 9
## Level - 10
## Level - 11
## Level - 12
## Level - 13
## Level - 14
## Level - 15
## Level - 16
## Level - 17
## Level - 18
## Level - 19
## Level - 20
## Level - 21
## Level - 22
## Level - 23
## Level - 24
## Level - 25
## Level - 26
## Level - 27
## Level - 28
## Level - 29
## Level - 30
