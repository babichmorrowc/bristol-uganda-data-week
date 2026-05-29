# Committing, pulling, and pushing

This document covers the process of editing your files, tracking those changes, and syncing them up with the remote repository. This is the heart of the version control process.

The following diagram shows the process:

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/2b82f5e2-acb3-458f-96ef-280039d07ba4" />

In general, the flow works in the following way:

+ You **pull** from the remote repository to your local computer to get all of the changes onto your computer
+ You edit the files as you see fit
+ You **add** them so that Git starts tracking the changes
+ You **commit** those changes, writing a *commit message* to describe what you have done
+ You **push** those changes from your local computer to the remote repository so that they are visible on GitHub (allowing for a back-up and collaboration)

## Using RStudio

You have some practice with adding and committing using Git from the command line. We will now learn how to use RStudio for this process.

+ Go to the Git pane of your RStudio and click on `Pull` to make sure you have the most up-to-date version of the code from the remote repository.
+ Create a new R script: File > New File > R Script.
+ Write your name at the top of the file, preceded by `#`, e.g. `# Cecina Babich Morrow`.
+ Save the file in the `intro-to-git-github/branching-practice` folder and name it after yourself, e.g. `cecina_babich_morrow.R`.
+ Look in the Git pane of your RStudio. The new file should now appear in that pane.
+ Click on the checkbox next to that file: this effectively runs `git add` for that file.
+ Click on `Commit`. Write an informative commit message.
+ Click on `Push` to sync those changes with the remote repository.
+ Click on `Pull` again.

Check both GitHub and your local computer: are you now seeing your new file in both places? Are you seeing other people's files appearing in both places?
