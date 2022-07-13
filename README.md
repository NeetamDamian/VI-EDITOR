# VI EDITOR

The vi editor is available in almost all the linux distributions. The command to open vi editor is 

`vi <file_name>`

The above command creates a new file if the given filename doesn’t already exists but if it exists the command will open the file.

The VI editor has 3 modes
* The Command mode
* Insert mode
* The last line

## The Command mode 

When you open a file with the vi editor, you will be taken to the command mode by default. In this mode you could issue commands to the editor such as copy, paste delete a line or word, you could also navigate in the text.

## Insert mode

We use the lowercase i to switch from the command mode to the insert mode. This mode allows you to edit file, add text, remove text. Once you are done to switch back hit the esc key.

## The last line

From the command mode the colon key takes you to the last line where you could choose to save file, discard changes and exit vi editor.

## Moving in the vi editor 
Apart from using the direction keys, the following can be used for navigation in the vi editor.

| Commands | Descriptions                         |
|----------|--------------------------------------| 
| k        | moves the cursor one line up.        |
| j        | moves the cursor one line down       |
| h        | moves the cursor one character left  |
| l        | moves the cursor one character right |

> `N/B`  vi is case sensitive

## Commands 

In the command line to copy a line move the cursor to the intended line and press yy (ie y twice)

To paste move the cursor to the line you want to paste to and press the p key.

To save the file use upper case ZZ ( twice )

To delete a letter/character move the cursor to the intended letter and press x and to delete the entire line use dd (twice)

To delete 3 lines use d3d

To undo press u

Redo CTRL + r

To find a string either slash or question mark. e.g /line to find the word line in the text and to go to the next occurrence the word line press n To find previous N.

The question mark also finds but it finds upwards.

To scrow up or down use the CTRL + u or CTRL + d respectively.
Typing colon ( : ) will take you to the last line.



Below are some of the last line commands.

|Commands | Descriptions        |
|---------|---------------------|
|:w       | save                |
|:q       | exit                |
|:wq      | save and exit       |
|:q!      |quit without save.   |

An improved version of vi editor now available is Vim

Vim = Vi improved.  
