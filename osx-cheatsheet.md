# Cheat-sheet OsX
###Shortcuts

| Key/Command | Description                                                                                            |
|-------------|--------------------------------------------------------------------------------------------------------|
| Ctrl + A    | Go to the beginning of the line you are currently typing on                                            |
| Ctrl + E    | Go to the end of the line you are currently typing on                                                  |
| Ctrl + L    | Clears the Screen                                                                                      |
| Command + K | Clears the Screen                                                                                      |
| Ctrl + U    | Clears the line before the cursor position. If you are at the end of the line, clears the entire line. |
| Ctrl + H    | Same as backspace                                                                                      |
| Ctrl + R    | Lets you search through previously used commands                                                       |
| Ctrl + C    | Kill whatever you are running                                                                          |
| Ctrl + D    | Exit the current shell                                                                                 |
| Ctrl + Z    | Puts whatever you are running into a suspended background process. fg restores it.                     |
| Ctrl + W    | Delete the word before the cursor                                                                      |
| Ctrl + K    | Clear the line after the cursor                                                                        |
| Ctrl + T    | Swap the last two characters before the cursor                                                         |
| Ctrl + F    | Move cursor one character forward                                                                      |
| Ctrl + B    | Move cursor one character backward                                                                     |
| Esc + F     | Move cursor one word forward                                                                           |
| Esc + B     | Move cursor one word backward                                                                          |
| Esc + T     | Swap the last two words before the cursor                                                              |
| Tab         | Auto-complete files and folder names                                                                   |

###Core commands
| Key/Command                                   | Description                          |
|-----------|----------------------------------------------------------------|
| cd             | Home directory                                                            |
| cd [folder]    | Change directory                                                          |
| cd ~           | Home directory, e.g. ‘cd ~/folder/’                                       |
| cd /           | Root of drive                                                             |
| ls             | Short listing                                                             |
| ls -l          | Long listing                                                              |
| ls -a          | Listing incl. hidden files                                                |
| ls -lh         | Long listing with Human readable file sizes                               |
| ls -R          | Entire content of folder recursively                                      |
| sudo [command] | Run command with the security privileges of the superuser (Super User DO) |
| open [file]    | Opens a file ( as if you double clicked it )                              |
| top            | Displays active processes. Press q to quit                                |
| nano [file]    | Opens the Terminal its editor                                             |
| pico [file]    | Opens the Terminal its editor                                             |
| q              | Exit                                                                      |
| clear          | Clear screen                                                              |

###Command History

| Key/Command                                   | Description                          |
|-----------|----------------------------------------------------------------|
| history n | Shows the stuff typed – add a number to limit the last n items |
| ctrl-r    | Interactively search through previously typed commands         |
| ![value]  | Execute the last command typed that starts with ‘value’        |
| !!        | Execute the last command typed                                 |

###File management

| Key/Command                                   | Description                          |
|-----------------------------------------------|--------------------------------------|
| touch [file]                                  | Create new file                      |
| pwd                                           | Full path to working directory       |
| ..                                            | Parent/enclosing directory, e.g.     |
| ‘ls -l ..’ = Long listing of parent directory |                                      |
| ‘cd ../../’ = Move 2 levels up                |                                      |
| .                                             | Current folder                       |
| cat                                           | Concatenate to screen                |
| rm [file]                                     | Remove a file, e.g. rm [file] [file] |
| rm -i [file]                                  | Remove with confirmation             |
| rm -r [dir]                                   | Remove a directory and contents      |
| rm -f [file]                                  | Force removal without confirmation   |
| rm -i [file]                                  | Will display prompt before           |
| cp [file] [newfile]                           | Copy file to file                    |
| cp [file] [dir]                               | Copy file to directory               |
| mv [file] [new filename]                      | Move/Rename, e.g. mv -v [file] [dir] |


###Folder management

| Key/Command                                   | Description                          |
|-----------------------------------------------|--------------------------------------|
| mkdir [dir]          | Create new directory                                    |
| mkdir -p [dir]/[dir] | Create nested directories                               |
| rmdir [dir]          | Remove directory ( only operates on empty directories ) |
| rm -R [dir]          | Remove directory and contents                           |

###Geting help
| Key/Command      | Description                          |
|------------------|--------------------------------------|
| [command] -h     | Offers help                               |
| [command] —help  | Offers help                               |
| [command] help   | Offers help                               |
| reset            | Resets the terminal display               |
| man [command]    | Show the help for ‘command’               |
| whatis [command] | Gives a one-line description of ‘command’ |

