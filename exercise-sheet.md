# Using Git and GitHub effectively

The central repository for this practical will be: https://github.com/Research-Software-Kent/git-and-github-material

This contains a file `names-and-food.md` which we want to contain a list of people's names (you can use a fake name!) and a list of favourite foods (with duplicates removed), which are split into two sections.

The task is to update the file utilising forks, branches, and local changes propagated to the remote repository and then back again, propagating all the changes to our local repositories to reach __eventual consistency__: everyone with the same local view of the files.

You will need a GitHub account if you don't already have one.

* Make an issue on the central repo about your data being missing.
* Fork the central repo and make a local copy (your choice of method).
* Make a new branch (e.g., using `git branch name`) for your changes.
* Make your local updates to the file and split your change into two commits by using `git add -p`

Use this as an opportunity to check you can also use
 `git reset` (i.e., stage a change then restore it to the index).

Create two suitable commits referencing your original issue, one for the names and one for the food (with the last __closing it__).

If you do something wrong reset the commit and try again before pushing.

* Push and make a PR to the central repo. Include a helpful PR message.

