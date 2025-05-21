# Demo
https://www.youtube.com/watch?v=RGOj5yH7evk

## Pushing files from VS Code to repo
git clone https://github.com/sanjanarraju/demo-repo.git

cd demo-repo

ls -la

git status (see which files are untracked)

  - If there are untracked files:
    
  - git add .    OR      git add "file name"
    
git status

git commit -m "add a message"

git push


## Creating a new repo on VS Code

git init  (creates a new git repo)

git status

git add README.md

git status

git commit -m "Created Read.me"

git remote add origin https://github.com/sanjanarraju/demo-repo2.git

git remote -v

git push --set-upstream origin main


## Git Branching
git branch  (check which branch you're on - the branch you're on shud be starred and highlighted)

git checkout -b (name) --> EX: git checkout -b feature-readme-instructions

git checkout main  (switched back to "main" branch)

git diff     (shows the changes in your project)

git pull    (update local version of repo to the remote)

git commit -am "your message"    (this only works for files you modified)  (this command adds and commits at the same time)

git branch -d "name"    (deletes the branch)


## Undoing in Git

_Undo add_

git status

git add README.md

git status

git reset README.md

_Undo commit_

git add README.md

git commit -m "added step"

git reset HEAD~1

git log   (log of all the commits in reverse chronological order) (also shows the hashes of all the commits)

git reset "copy paste the hash of the commit you want to go back to"

git reset --hard "the hash"   (not just unstages the changes but completely removes)

## Forking

click on the fork button on github, to access other repos you don't have access to, so you can make updates or changes





