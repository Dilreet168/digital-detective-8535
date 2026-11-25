# Mission 2 - Become Comfortable With The Terminal

## 1. Task / objective
Practise using the command-line interface to inspect folders, create and manage practice files, and understand command flags, pipes, and package managers.

## 2. Work completed
I practised basic Terminal operations inside my assignment repository. I checked the current directory, listed files, created a practice folder and text file, added and displayed text, copied a file, and renamed the copy. I also compared a normal listing with a detailed listing, used a pipe to limit displayed output, and checked whether Homebrew was installed.

## 3. Commands / tools used
- `pwd` — displayed the current directory.
- `ls` — listed visible files and folders.
- `ls -la` — displayed a detailed listing, including hidden items.
- `cd ..` — moved to the parent directory.
- `mkdir -p` — created a practice directory.
- `touch` — created an empty file.
- `>` — wrote text to a file, replacing its contents.
- `>>` — appended text to the end of a file.
- `cat` — displayed a file’s contents.
- `cp` — copied a file.
- `mv` — renamed or moved a file.
- `head -n 5` — displayed the first five lines of input.
- `|` — sent one command’s output to another command.
- `brew --version` — checked the installed Homebrew version.

## 4. My understanding
The Terminal lets me interact with the computer by entering commands. `pwd` tells me where I am, and `ls` shows what is in a folder. The `-l` and `-a` flags change the information shown by `ls`: `-l` gives a detailed format, and `-a` includes hidden items. `cd ..` moves to the parent folder.

I learned that `>` replaces the contents of a file, while `>>` appends new text and keeps the existing contents. `cp` creates a separate copy, leaving the original in place. `mv` moves a file or changes its name. A pipe (`|`) sends the output of one command to another command. For example, `ls -la | head -n 5` sends a detailed listing to `head`, which displays only its first five lines.

A package manager helps install and manage software and its dependencies. Homebrew is a package manager used on macOS. I checked for it with `brew --version`, which displayed version 7.0.14. I did not install or uninstall software for this assignment.

## 5. Difficulties faced
I initially ran a file command from the wrong directory and had to check my location.

## 6. How I resolved them
I used `pwd` to check my current directory, then changed to the assignment folder before continuing.

## 7. Evidence / files
- `mission-02-terminal/README.md` — Contains the summary of the mission.
- `mission-02-terminal/terminal-practice/` — Contains the files i created and backup copy.
- `evidence` - Contains the screenshot of the Terminal work.
- `mission-020task.md` - Contains the observations of all four tasks.

## 8. Commit details
- Commit message: Complete Mission 2 Terminal practice
- Branch: main
- Pushed to GitHub: Yes
