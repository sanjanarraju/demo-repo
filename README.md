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

git checkout -b feature- (name) --> EX: git checkout -b feature-readme-instructions

git checkout main  (switched back to "main" branch)

git commit -am "your message"    (this only works for files you modified)  (this command adds and commits at the same time)


