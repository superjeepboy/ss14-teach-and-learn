# ss14-teach-and-learn
A dummy repository as an example for new PRs.

# What is the purpose of this repository?
This repository is accessible by anyone who wishes to learn how to make proper PRs and learn the Git version control system, from forking, making a PR, all the way to merge.


# The Absolute Basics
First, you will need to download the files to your PC in order to make any changes. You will need to obtain the git link for this repository, which you can get by clicking the green `Code` button and copying the link into the command `git clone (link here)`. Cloning is like downloading files from a remote server.

Git works on a "version" system in every repository - every version containing a set of changes. Every version is set chronologically from each commit. This is useful in keeping track of larger projects, with multitudes of files within it. If you ever make mistakes, you can always roll back!

Each repository also contains "branches", the idea that one person can still be moving forward with patches while you make specific changes in your own copy. Think of it as a split in a river, they all can lead back to the same origin eventually. Branches can also "merge" back into one another, creating the pull request system where people in charge of the original branch can review what goes on in your branch. Once everything's cleared, it gets merged!

You will need a GitHub account in order to make PRs, then you will have to make a new branch off of `main`. You can do this by running `git branch (branch name)` and then `git switch (branch name)`. This will put you in your own branch to work off of.

When you make changes, you will have to first add files to the version you are on. You can do this by running `git add .` Note that in some IDEs this will be done automatically when saving files if it is linked to a GitHub project. Then, in order to make the changes and log them down, you have to run `git commit`. This will create a version of your git project, essentially acting as a snapshot in that branch.

Once you have commits in your branch done, you can `git push`. This will make a pull request in your name, which you have to create on the website on the original repository, which then goes through review.

If you've done everything correctly, you've made your first PR!

## PR Prerequisites
There are a few key things to keep in mind before submitting a PR. None of your changes will be touching main.

Your objective after obtaining the files will be to make a new folder in the `characters` folder, with a .txt file in it. Name the folder your character name. All the prerequisites in the .txt file are as follows:

First, write down a small descriptor/backstory of that character plus your discord username to confirm that it is indeed you that is making the changes.

Secondly, make sure whatever changes you have made are committed to your fork.

Lastly, make a PR! Your PR will be accepted once all conditions are met.
