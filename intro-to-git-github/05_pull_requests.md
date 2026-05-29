# Pull requests

A pull request is a way for you to get the changes you've made to your code back into the original version of the repository. Let's say you've written some code on your branch to analyze the data. Once you push it to the repository, it's available on GitHubm for your branch, but it isn't integrated into the main copy of the code. If you submit a pull request, however, your code can be pushed to the original repository.

## Pull request practice

Once you and your partner have completed the instructions in the [Branching tutorial](https://github.com/babichmorrowc/bristol-uganda-data-week/blob/main/intro-to-git-github/branching.md), you are ready to try out a pull request!

1. Make sure all of your edits have been saved, committed, and pushed to the species branch (see instructions for **Typing --> Directing**).
2.  Go online to GitHub and switch to your branch by clicking on the button on the top left that says "Branch: **master**" and switching to the desired branch.  Click the "New pull request" button.
3. Add a description for the pull request and click "Create pull request".
4. In this case, I will perform this step by merging the pull request. You can check out [slides 49 - 53](https://github.com/jtr13/codehelp/blob/master/GitHubWorkflowPt2.pdf) to see how I do it.
5. I will also perform this step by deleting the merged branch on GitHub ([slide 55](https://github.com/jtr13/codehelp/blob/master/GitHubWorkflowPt2.pdf)).
6. Finally, you should delete the merged branch on your computer. Using Terminal, navigate to the correct directory and run the following:
  + `git branch -d <branchname>` (without the < >, just insert the name of the branch)
  + `git fetch -p`
