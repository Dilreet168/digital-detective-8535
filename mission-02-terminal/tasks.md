## Task 2.1 — Basic Terminal operations
| Operation | Command |	What it does | Example observation |
| ... | ... | ... | ... |
| Show current folder | pwd	| Prints the path of the folder Terminal is currently in | It showed my project folder’s path |
| List files | ls |	Lists visible files and folders in the current folder | It showed the mission folders and README |
| Detailed listing | ls -la | Shows details and hidden items too | It showed permissions, owners, sizes, and hidden entries |
| Move to parent folder | cd .. | Moves up one directory level |	pwd showed the parent folder afterward |
| Create a folder |	mkdir -p | Creates a folder | The folder appeared in the listing |
| Create an empty file | touch notes.txt | Creates an empty file if it doesn’t exist | ls showed notes.txt |
| Copy a file |	cp notes.txt copy.txt |	Makes a copy with a different name | Both files appeared in the folder |
| Move or rename a file | mv copy.txt renamed.txt | Renames or moves the file |	The new name appeared in the listing |
| Display file contents | cat notes.txt | Prints the contents of a text file | It displayed the lines I had written | 

## Task 2.2 - Practice File Changes Safely
- Replacing file contents removes the old text and writes new text. Appending keeps the existing text and adds new text at the end. In Terminal, > replaces and >> appends.
- Copying creates a second file and keeps the original. Moving changes the file’s location; moving it to a new name renames it.
- The current-directory display shows the path of the folder Terminal is working in.
- A detailed directory listing shows extra information such as hidden files, permissions, owners, and file sizes.

## Task 2.3 Understand Flags And Pipes 
- A flag changes how a command works or what information it displays. For example, `-l` makes `ls` show a detailed listing.
- A normal directory listing shows the names of visible files and folders. A detailed listing can also show hidden items and details such as permissions, owners, and sizes.
- In `ls -la | head -n 5`, the pipe (`|`) sends the output of `ls -la` to `head`.
- `head -n 5` displays only the first five lines, making long output easier to inspect.

## Task 2.4 Understand Package Managers

Homebrew is a package manager for macOS that helps users to manage software from Terminal . It can install, update, and remove supported programs, and it can manage dependencies—other components a program needs in order to work . Homebrew provides commands for checking and managing software, which can make setup and maintenance easier . I checked whether Homebrew was available by running `brew --version` and viewed its installed . I did not install or uninstall anything . 