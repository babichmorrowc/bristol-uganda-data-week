# Branching

Branching is one of the ways that Git offers to work on copies of code from a main set of code (the other method is forking, which we will not cover here).

Branching, as you can probably tell from the name, creates a "branch" from the main "tree" of the repository. Unlike a fork, this branch is connected to the main repository, which is what makes it so useful for us to use to collaborate on code. When you create a branch, you start off with all of the history of the main "tree": you have all of the files and commits from the repository up to the point the branch was created.

Once you create the branch, you can make changes to it (add files, edit files, even delete files) without changing those files on the main "trunk" of the repository (also known as the master branch). The branch is then (semi-)independent from the main code in the repository. If the code you write doesn't work, you can delete the branch and continue on your merry way without having damaged the code in the master branch. If you do like what you write on the new branch, you have the ability to later merge that branch with the master branch, incorporating your edits into the main code of the repository.

## Network graph

GitHub allows us to view a "network graph" for the repository, which is a nice way to visualize what is going on with branches, forks, etc. You can see the network graph for our repository here: https://github.com/babichmorrowc/bristol-uganda-data-week/network. The line at the top represents the main version of the repository, which you can think of as the trunk of the tree. The dots along the line represent each commit: you can hover over these to read the commit message. As we create branches, they will also appear on the network graph and you can see how they relate to the main copy of the code.

## Creating a branch

As per usual with GitHub, there are several ways to create a new branch. For today, we will use RStudio to do so.

Get into pairs. For this exercise, we are going to be doing "strict pair programming", which means only one person in your pair will be typing on the code at a time. The other person can be looking through their code to tell the typer what to type. Essentially, one partner is typing and the other is directing, i.e. telling them what code to write.

Partner #1 will click on the "New Branch" button in RStudio. Name this branch after you and your partner, then click "Create"
