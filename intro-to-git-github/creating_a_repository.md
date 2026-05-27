# Creating a repository

A Git repository is a directory with version control. The local version of the repository lives on your computer, where you make all of your edits to the files. The remote repository is hosted on a server, in our case GitHub, and allows you to share your work, collaborate, and back up your progress.

## Creating a repository, local first

When we started out with the UKRN training, you created a local Git repository by using the `git init` command in terminal ([Creating directories](https://bristol-training.github.io/ukrn-intro-git-github/pages/300-directory.html)). That `init`ialised a local Git repository on your computer. It did not do anything with your GitHub account, however. If you want your local repository to "talk to" a remote repository on GitHub, you need to create a remote repository.

## Creating a repository, remote first

If you instead want to create the remote version of the repository first, on GitHub, you start by logging in to [https://github.com](https://github.com) and then clicking on the green "New" button next to "Repositories". Below is a screenshot of what I filled in to create this repository: 

<img width="761" height="691" alt="image" src="https://github.com/user-attachments/assets/5b2c3436-7318-4c28-b274-80778247085f" />

Note a couple of things:

+ I have initialised the repository with a README file, which is just a file where you can add a description and useful information about your project. You can find the README for this repository [here](https://github.com/babichmorrowc/bristol-uganda-data-week/blob/main/README.md).
+ I added a `.gitignore` file using the template that GitHub helpfully provides for R. This file can be used to tell GitHub what *not* to track so that your repository is not cluttered with files that you don't actually want or need to version control. There are templates for other languages as well. 
