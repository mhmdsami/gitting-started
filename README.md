# Getting started with Git & GitHub

## Git & GitHub: An overview
- Git: In a nutshell.
- GitHub: Home to most OSS.
- Alternatives to Git.
- Alternatives to GitHub.

## Getting Started with Git
## Installing [`git`](https://git-scm.com/)
### Linux
Debian/Ubuntu
```
apt-get install git
```
Fedora
```
yum install git
```
Arch Linux
```
pacman -S git
```
### Windows
Install using the [Windows Installer](https://git-scm.com/download/win)
or using `winget`
```
 winget install --id Git.Git -e --source winget
```
### MacOS
using `homebrew`
```
brew install git
```
## Configuring `git`
```
git config --global user.name [name]
```
```
git config --global user.email [email]
```
## Few Commands in `git`
- command: `git init`
```
git init
```
- command: `git add`
```
git add [filename|dirname]
```
```
git add *.js
```
```
git add .
```
- command: `git status`
```
git status
```
- command: `git commit`
  - Writing good commit messages.
```
git commit -m [commit_message]
```
- command: `git log`
```
git log
```
- command: `git remote`
```
git remote add [remote_name] [remote_url]
```
```
git remote remove [remote_name]
```
```
git remote -v
```
- command: `git clone`
```
git clone [url]
```
- command: `git branch`
```
git branch <branch_name>
```
- command: `git checkout`
```
git checkout [branch_name|id|HEAD]
```
- command: `git push`
```
git push [remote] [branch]
```
- command: `git pull`
```
git pull <remote> <branch>
```
- other commands: `git diff`, `git stash`, `git restore`, `git fetch`, `git rm`, `git rebase`, `git blame`, `git tag`

## GitHub: A quick view
- Creating an account
- Creating a repo
- Pushing changes to the repo
- Pull Requests
- Code Reviews
- Issues
