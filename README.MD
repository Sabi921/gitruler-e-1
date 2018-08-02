<!--
Marked Style: Github
-->

# GitRuler Section C

This repository is section C of the [GitRuler exercises](https://github.com/UOL-CS/gitruler-exercises).

In this exercise we will learn about moving and removing files within a repository and telling git to ignore a set of files.

## Introduction

If you do not already have a your own repository for these exercises [fork this repository](https://help.github.com/articles/fork-a-repo/). Clone this repository

At any time you can run gitruler to check your progress. From the command line run:

`java -jar <path to gitruler.jar>`

For more information on running gitruler look at the [project repository](https://github.com/rcraggs/gitruler).

## Instructions

1. After cloning the repository change into the directory on a [command line](https://www.techopedia.com/definition/3337/command-line-interface-cli).
2. Run gitruler to initialise the exercise.

In these exercises we'll imagine that our shop-keeper is opening shops in new locations. To plan these, branches of master are used.

## Branching and working within a branch

1. Branch the repository to [create a new branch](https://githowto.com/creating_a_branch) called `new-location-1` from `master`.
2. In the `new-location-1` branch add "Sunny Rosario" to a new row in `files/employees.txt`. Commit that change with the message "Add employee Sunny"
3. [Switch back to](https://githowto.com/navigating_branches) the `master` branch add a new file called `files/products.txt` with the contents "Bananas". Commit this file with the message "Add products file".
4. [Merge all changes](https://githowto.com/merging) from the `master` branch into the `new-location-1` branch.
5. Merge all changes from the `new-location-1` branch into the `master` branch.

## Submitting the results

Once the exercise is complete, push this repository to the remote. If there are multiple branches for an exercise, make sure that you push them all. 

To ensure that you have you correctly pushed everything that you need to, you could clone the remote repository into a separate folder and re-run gitruler.

## Resources

1. Creating branches: [https://githowto.com/creating_a_branch](https://githowto.com/creating_a_branch).
2. Switching between branches: [https://githowto.com/navigating_branches](https://githowto.com/navigating_branches).
3. Merging changes from one branch to another: [https://githowto.com/merging](https://githowto.com/merging).