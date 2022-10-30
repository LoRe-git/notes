# Git notes

## Clone:

### From URL:
Specific branch:

git clone -b <branchname> <remote-repo-url>
  
Clone all branches:
  
`git clone https://<username>@github.com/<userid>/<reponame>`


## Branches:

Show all branches: `git branch -vva`

Checkout a branch: `git checkout <branchname>`

## Stash:

List all stashes: `git stash list`

Apply stash: `git stash apply stash{0}`

## Commit:

Add the changes to stage: `git add <file1> <file2> ...`

Commit: `git commit -m "<Commit message>"`

push: `git push`


## Config:

Changing Committer Name & Email Globally: 
`git config --global user.name "<Name>"`   
`git config --global user.email "<Email>"`

Changing Committer Name & Email per Repository: `git config user.name "<Name>"`  `git config user.email "<Email>"`
