0. 'cd thecmdchallenge' -> Get inside the thecmdchallenge/ directory
1. 'pwd' -> print current directory path
2. 'ls -a' -> List all the files from the current directory including the hidden ones
3. 'ls -R' -> Now list all the files inside the project, recursively (all files in the hierarchy)
4. 'clear' -> Clear all the clutter from the command line
*. 'find . -type d -name small-name' -> find directory "small-name"
*. 'find . -type f -name trophy.txt'  -> find directory "trophy.txt"
5. 'cat URL'  -> show on the console the content of the trophy.txt file
*. 'cd ..' -> Move one level up
6. 'ls *.js' -> list all files with the JavaScript typical extension
7. 'mkdir not-that-funny' -> Create a new directory called “not-that-funny“
8. 'cp ./thecmdchallenge/boringfolder/even-more-boring/i-cant-believe-how-boring/the-ultimate-boring-inception/the-mostboring-text.txt ./thecmdchallenge/funcode/the-most-funny/not-that-funny/lol.txt' -> Create a copy of the-mostboring-text.txt and name it lol.txt 
9. 'mv ./funcode/kids.jpg ./funcode/images/hello/' -> Move funcode/kids.jpg inside funcode/images/hello/
10. 'rm -R small-name' -> Remove the "small-name" directory 
11. 'cat ./funcode/the-most-funny/lol/the-ultimate-joke.txt' -> Print in the command line the content of the-ultimate-joke.txt
12. 'rm -r ./boringfolder' -> Remove the "boringfolder" directory 
13. 'vi kamehameha/dragon-ball-jokes.md' -> Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor
14. 'dd' & ':x' -> remove the first joke you read on the file, finally save and close the text editor
---
__VI EDITOR MAIN COMMANDS__
vi filename - edit filename starting at line 1
:x<Return> - quit vi, writing out modified file to file named in original invocation
:q!<Return> - quit vi even though latest changes have not been saved for this vi call
j or <Return>
  [or down-arrow] - move cursor down one line
k [or up-arrow] - move cursor up one line
h or <Backspace>
  [or left-arrow] - move cursor left one character
l or <Space>
  [or right-arrow] - move cursor right one character
0 (zero) - move cursor to start of current line (the one with the cursor)
$ - move cursor to end of current line
u - UNDO WHATEVER YOU JUST DID; a simple toggle
i - insert text before cursor, until <Esc> hit
a - append text after cursor, until <Esc> hit
o - open and put text in a new line below current line, until <Esc> hit
O - open and put text in a new line above current line, until <Esc> hit
r - replace single character under cursor (no <Esc> needed)
x - delete single character under cursor
dd - delete entire current line