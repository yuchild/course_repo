# How to use git & the Galvanize curriculum
The material for each day is stored in a github repository linked from the schedule (in the "repo" column). Each day, once the repo is released, you will fork that repo to your personal github account, then clone (download) your fork onto your personal computer.

Then you will work on the day's coding assignments (the fun part!). When you are done, you will push (upload) your work to your fork on github. Finally, you will make a pull request (by clicking "new pull request" from your fork on github) so the instruction team can keep track of your progress.

# How to add work to your repo
Each day has an individual sprint and a paired sprint. To ease collaboration, each time you start a sprint you will first make a new branch for storing your work. At the end of the day, you will merge all your work into the `master` branch.

## How to make a new branch
- (here are some useful tutorials on git branching: https://learngitbranching.js.org/ and https://www.atlassian.com/git/tutorials/using-branches)
- After forking and cloning, navigate to the repo folder in your terminal.
- Start your day by typing `git checkout -b individual`. This makes a new branch called `individual` where you will store your work on the morning sprint.
- To see all branches, local & remote, along with their latest commits, type `git branch -avv`. Your current branch is marked with an asterisk `*`. If you have just cloned a repo, by default you'll be on the `master` branch. To switch to a branch, type `git checkout branch-name`.
- In general, to create a branch, type `git checkout -b branch-name`. This will create a new branch starting from the current state of your current branch. Note that branch names cannot contain spaces.
- Then: work on stuff! Write code using your favorite text editor: atom, sublime, vim, or emacs.

## The ABCs of git: Always Be Committing
git keeps tracks your work with _commits_. A commit should be the smallest useful unit of change to your codebase. That way, whenever you find yourself having written intractably broken code, you can revert to the last commit that worked.
- `git status` will show files with changes that haven't been committed yet
- `git add <file-name>` will stage the file `<file-name>` for committing.
- `git commit -m "informative commit message"` will commit the changes. The commit message is required! Make it informative, like `add finished assessment files` or `fix typo in data_clean() docstring`. See [this page](https://chris.beams.io/posts/git-commit/#imperative) for more tips.
  - If you don't type a commit message, you'll be forced to enter one in vim, the best text editor. If you are stuck in vim, pres `<Esc>` twice to ensure that you are in command mode, then type `:q` and enter.

## Pushing your local files to github
`git` is not Github. To keep your remote repo (the one on Github) in sync with your local repo (the one on your computer), you upload your files with `git push ...`
- `git remote -v` will show all the remote repositories associated with your local repo. By default, the repo URL you cloned from gets the alias `origin`.
- `git push <remote-name> <branch-name>` will push the branch `<branch-name>` to the remote `<remote-name>`
  - for example, `git push origin master` or `git push origin individual`
  - the first time you push a new branch, type `git push -u <remote-name> <branch-name>`. The `-u` is short for `--set-upstream`, meaning that it creates a remote branch for your local branch to track.

# How to share work (for pair programming)
First, choose **one person's** github repo to work in for the duration of the paired sprint. For convenience, let's call that person `A`.
The other person will be person `B`.

If you are person `A`, add your partner as a collaborator on github.
- go to your fork on github, click "Settings", then "Collaborators & teams", then type your partner's github username in the text box at the bottom of the page

If you are person `B`, add your partner's github repo as a remote to your local repository. **This should be done from the same folder (repo) in which you were working on the morning individual sprint**:
- if you haven't already as part of the morning individual sprint:
   - fork the day's github repo from GalvanizeDataScience into your personal github account
   - go to your fork on github, click "Clone or download", copy the URL that pops up. Using your terminal, clone the folder onto your computer.
- in your terminal, navigate to the day's folder. (This is the same folder you have just cloned per above or per the morning sprint)
- go to your partner's fork on github, click "Clone or download", and copy the URL that pops up
- in your terminal, type `git remote add <partner-name> <partner-remote-URL>`

Now you are both set up to push and pull from each other's github repositories! Collaboration!

If you are `A`:
- type `git checkout master`, then `git checkout -b pair`. This creates a new branch called `pair` based on `master` (so it won't contain your morning work).
- Start working together! Code up some stuff!
 - upload your work with `git add ...`, `git commit -m "useful commit message"`, `git push -u origin pair` (remember, you only need `-u` the first time you push a new branch)

After 30 minutes or so, switch the "driver/navigator" roles (this is different from person `A` and `B` - those roles will not change during the pair sprint)

If you are person `B`:
- in your terminal, navigate to the day's folder and type the following to download the latest work to your computer:
 - `git fetch <partner-name>`
 - `git checkout --track <partner-name>/pair`
- To push to `A`'s branch after making changes to it, type
 - `git push <partner-name> pair`

Continue working, switching driver/navigator roles roughly every 30 minutes.

If you are `A`:
- `git checkout pair` just to make sure you're on the right branch
- `git pull origin pair` to download changes that your partner made
- `git push origin pair` to upload changes

If you are `B`:
- `git checkout pair` just to make sure you're on the right branch
- `git pull <partner-name> pair` to download changes that your partner made
- `git push <partner-name>  pair` to upload changes

# Merging at the end of the day
At the end of the day, each person should have all of the day's work in their own `master` branch.

First merge the `pair` branch into the `master` branch
- `git checkout master`
- If you are `A`: `git merge -m "merge message" pair`
- If you are `B`: `git merge -m "merge message" <partner-name>/pair`
- `git push origin master` (pushes the merges you made to GitHub)

If merge conflicts come up, you have two options:
- Fix them! `git status` will tell you which files you need to edit. You'll see both versions of the file, and you'll have to delete the lines you don't want. Once you resolve the conflicts, you must `git add` and `git commit` the changes.
- Forget the whole thing! `git merge --abort` resets you to the state you were in before you tried to merge.

Whew!

# The .gitignore file
Sometimes you'll have files in a repo that you don't want git to track (or push to GitHub). You can tell git to ignore these files by making a file called `.gitignore` in your repo's root directory. An example `.gitignore` file might look like this:
```
*.pyc
*.zip
.ipynb_checkpoints
```

This tells git to ignore all files with `.pyc` and `.zip` extensions, as well as the folder `.ipynb_checkpoints`. See more documentation [here](https://git-scm.com/docs/gitignore)

# Troubleshooting

- If you accidentally clone from the gschool version rather than your fork, you will get the error `Repository not found`. This is a poor error message. What they really mean is that you don't have access to edit the repo. Here's what you can do:
  - `git remote add <your-username> <your-fork-URL>`
  - `git push <your-username> <branch-name>`

- In general, if you want to push a local branch to a remote branch with a different name, try:
  - `git push <remote-name> <local-branch-name>:<remote-branch-name>`

- If you really only want to copy one file from a branch and you know that trying to merge the whole branch would throw a bunch of conflicts, you can type
  - `git checkout <other-branch-name> -- path/to/file`

  - But make sure you don't have a file with this same name already, otherwise you will lose uncommited changes.
