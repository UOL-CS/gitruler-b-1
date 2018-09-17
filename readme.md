<!--
Marked Style: Github
-->

# GitRuler Section B

This repository is section B of the [GitRuler exercises](https://github.com/UOL-CS/gitruler-exercises). If you do not already have a your own repository for these exercises [fork this repository](https://help.github.com/articles/fork-a-repo/). 

In this exercise we will learn about tracking new files and creating commits with that contain selected changes.

## Creating and committing a new file

1. Run GitRuler to initialise the exercise.
1. Create a new file within in the `files` directory called `customers.txt` containing the text "El Rancho Burger".
2. Stage and commit this new file with the commit message "Add El Rancho".
3. Add another customer to this file called "Zorba's Palace" and commit that with the message "Add Zorba".

## Using git status to find and commit only newly created files

The `files/products` folder contains some files that describe products. Some of these are already tracked by git when you cloned the repository. Some files were added and others were edited when you ran gitruler.jar. These tasks are about committing the right changes in the right commits.

1. Use the [git status](https://githowto.com/checking_status) command to identify which of the files from `files/products` are currently untracked and which are tracked but modified.
2. Stage and commit the product files that are untracked with the commit message "Add new products".
3. Stage and commit the product files that are tracked but modified with the commit message "Update products".

## Submitting the results

Once the exercise is complete, push this repository to the remote. If there are multiple branches for an exercise, make sure that you push them all. 

To ensure that you have you correctly pushed everything that you need to, you could clone the remote repository into a separate folder and re-run gitruler.