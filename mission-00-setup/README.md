# Mission 0 - Create the GitHub workspace
## Task
Set up the project workspace and git repository.
Create folders for all missions.
## Work Completed 
I created the project and mission folders, added README files, initialized Git, made the first commit, and pushed the main branch to GitHub.
## Commands
- `mkdir -p` — created folders.
- `touch` — created files.
- `pwd` - print the working directory.
- `git init -b main` — initialized Git.
- `git add .` — staged the files.
- `git status` - shows which files have changed,staged, or still need to be committed.
- `git commit` — saved a snapshot of the setup.
- `git push -u origin main` — pushed the branch to GitHub.
## My Understanding 
- Git tracks changes to files in your project.
- A commit saves a snapshot of selected changes in your local repository.
- Push uploads those commits to GitHub so they’re backed up and visible online.
## Difficulties faced
I had to authenticate before GitHub would accept my push.
## How I resolved them
I initially entered the git add command incorrectly, so Git did not stage my files. I corrected it to git add . and checked git status to confirm the files were staged. I then created the initial commit. My first push was rejected because I had not authenticated with GitHub. I signed in using GitHub CLI and pushed the main branch successfully. I checked that the working tree was clean afterward.
## Evidence/files
- Root `README.md` with the project description and mission index
- Mission folders with their README files
- Initial setup commit pushed to GitHub
## Commit details
- Commit message: Set up Digital Detective mission structure
- Branch: main
- Status: Pushed to GitHub

