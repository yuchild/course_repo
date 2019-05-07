# Git Daily Workflow
An example of the daily git workflow for the DSI class.

# tl;dr Version

## Working in pairs

1. Fork the afternoon repo 
    * in browser
2. Clone forked repo onto your local machine 
    * `git clone <repo url>`
3. Create pair branch
    * `git checkout -b <pair branch name>`
4. Add each other's remotes to your local repo
    * `git remote add <alias> <your partner's repo url>`

### First Driver
**Assumes you did all steps in Before Starting Work**

1. Do work, follow ABC (Always Be Committing)
    * `git status` (check for your modifications)
    * `git add <file you changed>` (repeat for all files)
    * `git commit -m "<commit message>"`
2. Push initial work to ***your*** remote repo
    * `git push <your remote> <your local pair branch name>:<your remote pair branch name>`
        * The name for ***your*** remote will be `origin` by default.

### Second Driver
**Assumes you did all steps in Before Starting Work**

1. Pull your ***partner's*** work onto your local machine
    * `git pull <partner's remote alias> <partner's pair branch name>`
        * Merges your partner's changes onto your *currently checked out branch.*
2. Do work, follow ABC (Always Be Committing)
    * `git status` (check for your modifications)
    * `git add <file you changed>` (repeat for all files)
    * `git commit -m "<commit message>"`
3. Push the new changes/commits to ***your*** remote repo
    * `git push <your remote> <your local pair branch name>:<your remote pair branch name>`

### Repeat Second Driver Steps to infinity (or 'til you go home)





# All the Dirty Details Version

1. Fork repo for the afternoon
    * in browser
        * Forking is just a fancy way of saying "make a copy of this repo."
        * Necessary so you can push changes to your own remote repo, sorry we can't let you push to the Galvanize repos...
2. Clone repo onto local machine
    * `git clone <repo url>`
        * This copies the state of your remote repo onto your local machine and sets up a remote, `origin` by default, to pull or push changes.
3. Create pair branches
    * `git checkout -b <pair branch name>`
        * `git checkout -b <branch name>` is shorthand for two separate commands: `git branch <branch name>` followed by `git checkout <branch name>`
        * You can think of this command as saying "Make a new branch, then go point to it and track changes from there on."
        * `git checkout` tells your `HEAD` which commit it should point to. Usually you have it point to a branch, but you can technically have it point to any commit in your tree (or commits in remotes you are tracking).
4. Add each other's remotes to your local repo
    * `git remote add <alias> <your partner's repo url>`
        * This step can be done at any time before your first pull, but it is easier to get all the set up out of the way at the beginning of the exercise.
        * You don't have to specify an alias, but if you choose not to, every time you want to pull from a remote you'll have to use the full remote url.


### First Driver
**Assumes you did all steps in Before Starting Work**

1. Do work, follow ABC (Always Be Committing)
    * `git status` (check for your modifications)
    * `git add <file you changed>` (repeat for all files)
    * `git commit -m "<commit message>"`
2. Push initial work to ***your*** remote repo
    * `git push <your remote> <your local pair branch name>:<your remote pair branch name>`
        * The name for ***your*** remote will be `origin` by default

### Second Driver
**Assumes you did all steps in Before Starting Work**

1. Pull your ***partner's*** work onto your local machine
    * `git pull <partner's remote alias> <partner's pair branch name>`
        * Merges your partner's changes onto your *currently checked out branch*
        * git pull is shorthand for two separate commands: `git fetch <alias> <branch>` followed by `git merge`
        * `git fetch` downloads all the commits from the remote repo to your local repo and updates where your remote branch points. It doesn't change anything about your local branches. Running `git fetch` instead of `git pull` gives you flexibility to choose how to incorporate those changes (`git rebase` or other fancy git things) instead of being forced to use `git merge`.
2. Do work, follow ABC (Always Be Committing)
    * `git status` (check for your modifications)
    * `git add <file you changed>` (repeat for all files)
    * `git commit -m "<commit message>"`
3. Push the new changes/commits to ***your*** remote repo
    * `git push <your remote> <your local pair branch name>:<your remote pair branch name>`

### Repeat Second Driver Steps to infinity (or 'til you go home)
