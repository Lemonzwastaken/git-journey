Tracks my progress as I learn GIT


🧱 Setup & Repo Basics

git init                # initialize a repo
git clone <url>         # clone an existing repo
git config --global user.name "Your Name"
git config --global user.email "you@email.com"

📂 Checking Files & Status
ls                      # files in folder
git status              # repo state (most used)
git ls-files            # tracked files only
git ls-files --others   # untracked files
ls -R                   # checks hidden files

➕ Adding & Removing Files
git add file.txt        # stage one file
git add .               # stage everything
git rm file.txt         # remove tracked file
rm file.txt             # remove untracked file

Undo staging:
git restore --staged file.txt

✅Committing
git commit -m "message"
git commit -am "msg"    # add + commit (tracked files only)

🪹Branches
git branch              # list branches
git branch new-branch   # create branch
git checkout new-branch # switch branch
git checkout -b new     # create + switch

🔀 Merging & Rebasing
git merge branch-name
git rebase branch-name

🆘 Emergency Commands
git stash              # save work temporarily
git stash pop          # restore stash
