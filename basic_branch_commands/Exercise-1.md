# Basic Branching commands

## Setup

1. Create a new repository. Add a readme file.
2. Edit the readme file and commit changes.
3. Create a local repository in local path
4. Create a Folder "Test1" in local path for local repository.
5. Type --> `git init`  --> to initialize the local repository.
6. The .git folder will be created.
7. To link local reporsitory and github repository type
      git git p "<<github repository url>>"
8. Type `git pull origin main` (Important to see the correct branch name).
9. To see all the files added to index type -->` git status`
10. To add the file type --> `git add <file name>`

## The task

Hint: `git switch` will make you switch from one branch to another.

1. Use `git branch` to see the two branches that are relevant for this exercise
2. What branch are you on?
3. Use `git branch mybranch` to create a new branch called _mybranch_
4. Use `git branch` again to see the new branch created.
5. Use `git switch mybranch` to switch to your new branch.
6. How does the output from `git status` change when you switch between the _master_ and the new branch that you have created?
7. How does the workspace change when you change between the two branches?
8. Make sure you are on your _mybranch_ branch before you continue.
9. Create a file called `file1.txt` with your name.
10. `Add` the file and `commit` with this change.
11. Use `git log --oneline --graph` to see your branch pointing to the new commit.
12. Switch back to the branch called _master_.
13. Use `git log --oneline --graph` and notice how the commit you made on the _mybranch_ branch is missing on the _master_ branch.
14. Make a new file called `file2.txt` and commit that file.
15. Use `git log --oneline --graph --all` to see your branch pointing to the new commit, and that the two branches now have different commits on them.
16. Switch to your branch _mybranch_.
17. What happened to your working directory? Can you see your `file2.txt`?
18. Use `git diff mybranch master` to see the difference between the two branches.

## Useful commands

- `git switch`
- `git switch -c`
- `git log --oneline --graph`
- `git branch`
- `git diff`

