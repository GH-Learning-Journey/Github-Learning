## Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo

If we wanted to create a new git repo in a new project we could create the folder and then initialize that repo with `git init`

```
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
# makes changes to readme.md
git status (to see what files are being tracked or not)
git add .  (git add all) or git add Readme.md

`git commit` -


## Cloning

By Github CLI, SSH, HTTPS

Since we are using github codespaces we will create a temp directory in our workspace

### HTTPS 

```sh
mk dir /workspace/tmp
```
git clone https://github.com/GH-Learning-Journey/Github-Learning.git 

## Cloning

We can clone in 3 ways: HTTPS, SSH, Github CLI

### HTTPS

```sh
git clone 

## Commits

`git commit` When we want to commit code which will open up the commit edit message block in the editor of choice

## Branches

## Remotes

## Stashing 

## Merging

## Add

When we want to stage changes that will be included in the commit we can use the . to add all possible files
```
git add .
```

## Reset

`git reset` allows you to move staged changed to unstaged. It reverts `git add .`

Adding another note b/c I'm not seeing it in my GH

## Status

`git status` shows which files will or will not be committed 

## Gitconfig File

The gitconfig file is what stores your global configurations for git such as email, name, editor and more. 

`git config --list --show-origin` Shows the contents of the git config file

`git commit -m "add another whatever you want"` which makes a commit with the commit message without opening editor

## Log

git log will show recent git commits to the git tree

## Push

When we want to push a repo to our remote origin
`git push`
