This project is my process of learning github

I've installed git, Github desktop, and sublime text as my text editor.

I've learned a lot through Git-it and the MIT Beaverworks Git course

I've created a separate repository, called RSH, to store my progress and future projects

I learned how to use github through terminal:
- navigate through directories -> cd <name>
- navigate to parent directory -> cd ..
- create new directory -> mkdir <name>
	- this creates a new directory with regards to the current directory 
- view files in directory -> ls
- initiate a repository in git -> git init
- check status and changes -> git status, git diff
- how to add changes -> git add <name>
- after adding changes, can check in git status, then can commit through-> git commit -m "title of commit", which will commit all added changes
- to add all changes, can do git add .
- git config, --global user.username, user.name, user.email 
- view remote (connection to github) -> git remote -v
- git push <remote> <branch>
- git pull <remote> <branch>
- git push takes from local and pushes onto github
- git pull takes from github and pulls it to local
- if there is no set remote, can use git remote add <remotename> <url>


- starting a project from github, can clone to local by using git clone <url>

- if forked, can add another upstream remote -> git add remote upstream <url>
- use git remote -v to check
- can pull from upstream using git pull upstream <name>

- branches are to work on a separate "version" that don't interfere with other branches
- git branch <name> to create new branch
- git checkout <name> to switch
- git checkout -b <name> to create and switch
- git branch lists it
- git branch -m <newname> to rename current branch
- git status shows what branch currently on


- how to add collaborators
- go to project on github, settings on top row, add collaborators

- see changes to remote before pulling in
- git fetch --dry-run

- how to merge
- first checkout (swap) into whatever branch we want to merge into (keep)
- git checkout <main branch name>
- git merge <other branch name>
- now we can delete the other branch
- git branch -d <name>

- can also delete on remote by using
- git push <remote name> --delete <other branch name>

