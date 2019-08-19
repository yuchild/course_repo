# Git Daily Workflow
An example of the afternoon git workflow for the DSI class.

## Afternoon

### Before Starting Work (Both Partners Do This)

1. Fork galvanize repo for the day
    * in browser
2. Clone repo onto local machine
    * `git clone <repo url>`
3. Create a pair branch
    * `git checkout -b <pair branch name>`
4. Double check you are on pair branch before starting pair exercise
    * `git branch`
    * (if not on pair branch) `git checkout <pair branch name>`
5. Add each other's remotes to your local repo
    * `git remote add <alias> <your partner's repo url>`
    * We reccomend `pair` as an easy remote name.
    * If you have two partners, your partners initials would also work.

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


