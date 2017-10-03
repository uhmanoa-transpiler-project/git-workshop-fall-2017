# git-workshop-fall-2017
A dummy Git workshop using a website of the history of computer executable files.

- Create a page
- Learn how to use Git interactive add


# Activity 0 - Sign-up for GitHub, Fork the repo

- Sign-up for a GitHub repo
- Split into 2 teams
- The primary coder should rotate when you see **ROTATE**.
- **OPTIONAL** Install gource.


# Activity 1 - Create 2 separate websites (15m)

- Choose to make 1 of the following (as an entire team)
  - Before ELF (before-elf.html)
  - ELF (elf.html)

- Create a header.
- Create 1 paragraph.
- Create a 3 item list.

- DO NOT COMMIT.
- Do not do any styling yet.

# Activity 2 - Add/Reset
- `git add FILENAME`
- `git status`
- `git reset FILENAME`

# Activity 3 - Diff
- `git diff`
- `git diff --cached`

# Activity 4 - Log/Show
- `git log`
- `git log --oneline`
- `git log --oneline --graph`
- `git log --oneline --graph --decorate --color`
- `git show`

# Activity 5 - Push/Pull
- `git push origin master`
- **ROTATE**
- `git pull origin master`

# Activity 6 - Branch
- `git branch MYNAME-CHANGES`
- `git checkout MYNAME-CHANGES`
- `git log`
- Change the header contents on your webpage.
- Add 3 more items to your list.

# Activity 7 - Interactive Add/Patch
- `git add -i`
- `h`
- Learn how to use interactive add!
- Alternatively, if you just want to use only patch:
- `git add -p FILES`
- Add the header, and only the 1st and 3rd item.
- `git commit`
- `git push origin MYNAME-CHANGES`
- Follow the instructions to create a new upstream branch

# Activity 8 - Merging back into master
- **ROTATE**
- Change to another person, have them pull the branch
- `git pull origin MYNAME-CHANGES`
- Go onto master
- `git checkout master`
- From master, merge changes from another branch
- `git merge MYNAME-CHANGES`
- Any conflicts?

# Activity 9 - Multiple merging
- Create headers for N more sections on your page on master (where N = number of people on your team)
- Add, commit, push them to master
- **ROTATE TO ALL OTHERS**
- Have every person work on a section on their own branch
- Have every person push their branch upstream to their own branch
- HAVE ONE PERSON CHANGE THE PAGE'S HEADER
- **ROTATE TO ORIGINAL**
- Have the person merge every new branch into master.
- Merge conflict? Manually edit the file to look the way you want, then save it,
  add it and commit your changes.

# Activity 10 - Git Rebase

- Create a branch called `rebase-practice`
- Go onto it.
- Go into `git rebase -i`
- Change a commit's message.

# Activity 10 - Squash
- go into `git rebase -i`
- Squash two commits into one.

# Activity 11 - Squash all
- Prepare a SINGLE commit.
- This can be nicer when you're looking to contribute to open-source projects


# Activity 12 - Pull Request
- Go back to master, make a new branch called `pull-request-PAGE-NAME`
- Push it upstream as a new upstream branch
- Go onto your fork on GitHub.
- Prepare the pull request to uhmanoa-transpiler-project/git-workshop-fall-2017

# Activity 13 - Code Review

# Activity 14 - Revisions
- Make the changes, and make a commit.

# Activity 15 - Merging
- Squash? Merge? Rebase?

# Activity 16 - Rebasing your work
- After I merge in to master,
- `git remote add <URL OF UPSTREAM REPO>`
- `git pull --rebase upstream master`

# Activity 17 - Gource?


