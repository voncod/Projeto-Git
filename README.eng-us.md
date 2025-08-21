## This project was created to practice essential commands and workflows using Git and GitHub

## Objectives of this test

- Learn how to initialize a repository (`git init`)
- Work with branches (`git branch`, `git checkout`)
- Perform merges and simulate conflicts
- Practice using push, pull, clone, and reset
- Use GitHub to manage versions and pull requests

## What I did

- Created fictional files (`texto_1.txt`, `texto_2.txt`, `sistemadelogin.txt`, etc.)
- Simulated merges with conflict resolution
- Tested commands such as:
  - `git init`, `git add`, `git commit`
  - `git branch`, `git checkout`, `git merge`
  - `git push`, `git pull`, `git clone`, `git reset`
  - Created pull requests on GitHub

## Learnings

- Understood the importance of branches for parallel development
- Learned the workflow: `add -> commit -> pull -> push`
- Gained experience resolving basic conflicts
- Got familiar with the GitHub interface

## Issues Encountered

While using Git, I encountered the following error when trying to execute `git push`:

> Updates were rejected because the remote contains work that you do not have locally...

This issue happened because the GitHub repository already had a `README.md` file (created during the repository setup), but my local repository did not have that version synchronized. I created my own local `README.md` using `touch`, but when I tried to push it, Git blocked the operation to prevent overwriting the remote content.

To fix this, I ran:

`git pull origin main`
`git push`



## Observations

- This project contains fictional files used only for version control practice
- It does not represent a real or functional software project
