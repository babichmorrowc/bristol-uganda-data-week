# Cloning a repository

Cloning is the process of making a copy of a particular repository on the cloud so that you can work on it locally:

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/34477d6b-3186-4ba2-8c38-347783a8332e" />

## Using RStudio

RStudio provides us a nice interface to interact with Git/GitHub for our R projects. We can use RStudio to clone a repository to our computers. Follow these instructions to clone this repository to your computer:

1. Start a new project in RStudio using File > New Project > Version Control > Git. In the "repository URL", paste the URL of this GitHub repository: https://github.com/babichmorrowc/bristol-uganda-data-week.git.
2. Make sure you put the project somewhere on your computer that you can find it later!
3. Click “Create Project” to create a new directory, which will be all of these things: a folder on your computer, a Git repository linked to a remote GitHub repository, and an RStudio Project
4. Check that all of the files from this repository are now visible on your computer

(Note: these instructions are modified from the [New project, GitHub first](https://happygitwithr.com/new-github-first) page of Happy Git with R)

## Using command line

You can also use the command line to clone a repository via the `git clone` command. This is what is happening under the hood when you use RStudio to clone the repository. We won't practice this today, but there are great instructions [here](https://happygitwithr.com/push-pull-github.html?q=clone#git-clone-command-line).
