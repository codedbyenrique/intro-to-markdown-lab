## How to Create a File Using the Terminal
### 1. Open Your Terminal
* Mac/Linux: Search for “Terminal” in your applications.
* Windows (WSL/Git Bash): Open WSL or Git Bash.

### 2. Navigate to the Desired Directory
Before creating a file, move into the folder where you want it stored:

`cd path/to/your/folder`


***Example***:

`cd Documents/projects`

### 3. Create the File

There are several commands you can use:

**Option 1**: `touch (empty file)
touch filename.txt`
* Creates an empty file named filename.txt.

* If the file already exists, it updates the file’s last modified date.

**Option 2**: `echo (file with initial text)
echo "Hello World" > file.txt`


* Creates file.txt containing “Hello World”.

**Option 3**: `nano (open in text editor)
nano filename.txt`


* Opens the file in the nano editor so you can start typing.

* Press CTRL + O to save, Enter to confirm, then CTRL + X to exit.

### 4. Verify the File

Check if the file exists with:

`ls`


You should see your new file in the list.

 #### *Quick Reference Table*
|Command |	Purpose |
| ------ | ----------- |
|`touch file.txt` |	Creates an empty file
|`echo "text" > file.txt`|	Creates a   file with initial content
|`nano file.txt` |	Creates/opens file |in nano editor|
|`ls` |	Lists files in current directory|
