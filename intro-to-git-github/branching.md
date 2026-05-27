# Branching

Branching is one of the ways that Git offers to work on copies of code from a main set of code (the other method is forking, which we will not cover here).

Branching, as you can probably tell from the name, creates a "branch" from the main "tree" of the repository. Unlike a fork, this branch is connected to the main repository, which is what makes it so useful for us to use to collaborate on code. When you create a branch, you start off with all of the history of the main "tree": you have all of the files and commits from the repository up to the point the branch was created.

Once you create the branch, you can make changes to it (add files, edit files, even delete files) without changing those files on the main "trunk" of the repository (also known as the master branch). The branch is then (semi-)independent from the main code in the repository. If the code you write doesn't work, you can delete the branch and continue on your merry way without having damaged the code in the master branch. If you do like what you write on the new branch, you have the ability to later merge that branch with the master branch, incorporating your edits into the main code of the repository.

## Network graph

GitHub allows us to view a "network graph" for the repository, which is a nice way to visualize what is going on with branches, forks, etc. You can see the network graph for our repository here: https://github.com/babichmorrowc/bristol-uganda-data-week/network. The line at the top represents the main version of the repository, which you can think of as the trunk of the tree. The dots along the line represent each commit: you can hover over these to read the commit message. As we create branches, they will also appear on the network graph and you can see how they relate to the main copy of the code.

## Creating a branch

As per usual with GitHub, there are several ways to create a new branch. For today, we will use RStudio to do so.

Get into pairs. For this exercise, we are going to be doing "strict pair programming", which means only one person in your pair will be typing on the code at a time. The other person can be looking through their code to tell the typer what to type. Essentially, one partner is typing and the other is directing, i.e. telling them what code to write.

When it's time to switch typing partners, the person typing needs to commit their changes and push them to the remote branch so the other partner can get a copy of those modifications, and the person directing needs to retrieve these edits to their computer.

*Switching from typing --> directing:*
1. Save your changes to the script. The file will then show up in the Git tab of RStudio.
2. Click the checkbox next to the file, and click the "Commit" button.
3. A window will pop up where you will be able to see the difference between the original file and what you have added. Compare these versions: do you like the edits you made?
4. Type a commit message in the "Commit message" box and then click the "Commit" button.
5. Click on the "Push" button with the green arrow: this will take that edit you just made and push it to the remote copy of the branch (the one you can see on the GitHub website).

*Switching from directing --> typing:*
1. Go to the Git window of RStudio and click on the blue arrow: this will pull the edits from the remote copy to your machine.
2. Open the script file. Check to see that the edits your partner made are there.

## Try it yourself!

**Partner 1:**
1. Click on the "New Branch" button in RStudio. Name this branch after you and your partner, then click "Create".
2. Open the R script you created in our Committing, pulling, and pushing practice and add your partner's name to the top of the script.
3. Follow the instructions above (*Switching from typing --> directing*) to save that edit and push it to the remote copy of the branch.

**Partner 2:**
1. Follow the instructions above (*Switching from directing --> typing*) to pull that edit onto your local copy of the branch.
2. Open your partner's R script file and add the date to the top of the script.


## Branching resources

+ Chapter about branching from Happy Git with R: https://happygitwithr.com/git-branches.html
+ Video about Git branching: https://www.youtube.com/watch?v=QV0kVNvkMxc 
