# Bandit
## L 0 to 1

* Found a readme file using ls.Used cat to read it.  NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

## L 1 to 2

Found a file named - . Used ./- to read it. rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

## L 2 to 3

To include the spaces in the filename used cat spaces\ in\ this\ filename. aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

## L 3 to 4

Move to inhere directory using cd. Use ls -a to list all the files in the directory. Use cat to read the file.
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

## L 4 to 5

Move to inhere directory using cd.
Use ls to list all files.
Find the file type of each file using file command.
Pass: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

## L 5 to 6

Move to inhere directory using cd.
Use find ./ -readable ! -executable -size 1033c command
-readable to search for readable file
! -executable to search for non executable files
-size 1033c to search for files/directories having size 1033bytes 
This will display the file having the above properties
Pass: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

## L 6 to 7

Use find / -user bandit7 -group bandit6 -size 33c command
-user to find bandit7
-group to find bandit6
-size 33c to find file/directories of size 33bytes
This will display a bunch of files/directories having access as denied except one
/var/lib/dpkg/info/bandit7.password
Pass: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

## L 7 to 8

Use the command cat data.txt | grep 'millionth'
grep is used to find the occurrence of something in the file
Pass: TESKZC0XvTetK0S9xNwm25STk5iWrBvP

## L 8 to 9

Use the command sort data.txt | uniq -c
sort has to be used because uniq command compares only adjacent lines
uniq -c gives the count of the unique lines
find the line having count 1
Pass: EN632PlfYiZbn3PhVK3XOGSlNInNE00t

## L 9 to 10

Use the command strings data.txt | grep '=='
strings is used to find the strings in the file.
grep is used to find the lines having ‘==’
Pass: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

## L 10 to 11

Use the command base64 -d data.txt
-d stands for decode
Pass: 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

## L 11 to 12

Use the command cat data.txt | tr [A-Za-z] [N-ZA-Mn-za-m]
tr command here translates the input. Here we are translating rot13
that is each letter is shifted by 13 places.
Pass: JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

## L 12 to 13

Create a ne directory using mkdir /tmp/bb123
Copy data.txt to bb123 using cp data.txt /tmp/bb123
Move to bb123 using cd /tmp/bb123 
Use command xxd -r data.txt > temp
This give us gzip file 
Change the file name to temp.gz
Use gzip -d temp.gz
Continue the process till we get a txt file
Pass: wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw








