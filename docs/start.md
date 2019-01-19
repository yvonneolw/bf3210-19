# Installation and Environment Setup

This document contains instructions about installing software needed for the course. Please follow the steps carefully.

## Version Control

Have you ever worked on a paper for class, and then realised (to your horror) that you had accidentally deleted a paragraph you wrote in an earlier draft?

As programmers, we want to avoid this situation. To that end, you will learn the very basics of version control using Git. Click [here](https://git-scm.com/video/what-is-version-control) for a good overview.

In this class, we will use [Sourcetree](https://www.sourcetreeapp.com/), which is a beginner-friendly program for using Git through a visual interface. Install the appropriate version for your operating system (Mac/Windows). Then, follow the tutorials:

* [Understand the interface](https://confluence.atlassian.com/get-started-with-sourcetree/understand-the-interface-847359069.html)
* [Version control and Sourcetree](https://confluence.atlassian.com/get-started-with-sourcetree/version-control-and-sourcetree-847359072.html)
* [Work using Git](https://confluence.atlassian.com/get-started-with-sourcetree/work-using-git-847359053.html)

Now let's test it out by cloning the repository that contains this document. Click `New...` and choose `Clone from URL`. Then use [git@github.com:codegakko/bf3210-19.git](git@github.com:codegakko/bf3210-19.git) as the URL. Was Sourcetree able to read the contents of the repository?

In the future, `pull` this repository using SourceTree to get the latest course materials each week.

## GitHub (or BitBucket)

You will be working in teams to complete projects, but how do you plan to share your code? Emailing each other code snippets should never be the answer, as it is a surefire way of introducing bugs. 

Git track your own changes to your project. Services like GitHub and BitBucket let you store the project code online, so that your teammates can contribute to the project using the Git clients on their own computers.

Both [GitHub](www.github.com) and [BitBucket](www.bitbucket.org) work well for this purpose. Here, we will show the steps for setting up a team repository using GitHub.

1. Ensure that every team member has created a GitHub account.
2. Delegate one member to create a public repository. They should click `+` at the upper-right corner of any page on GitHub, click `New repository`, and follow the instructions. ([More info](https://help.github.com/articles/create-a-repo/))
3. Have the member who created the repository add the other team members' GitHub accounts as collaborators. ([More info](https://help.github.com/articles/inviting-collaborators-to-a-personal-repository/))
4. Have each member clone the repository using Sourcetree. Now, you can each `push` and `pull` your code to the shared repository.

## Python

In this course, we will be programming using a language called Python. _Please follow these steps, even if your computer comes built in with a default Python distribution._

1. Download the Anaconda distribution of Python 3.7 [here](https://www.anaconda.com/download). **NOTE: Ensure you install version 3.7 for the correct operating system (Mac/Windows).**
2. Start the installer and follow the instructions. **NOTE: Use the default options. However, check the "Add Anaconda to my PATH environment variable" option if you are using Windows.**
3. Open your computer's default command line tool (Terminal for Mac, or PowerShell for Windows). Check that Python has been correctly installed by typing `python` and pressing `Enter`. Does it say `Python 3.7.1`?

## Text Editor

Install [PyCharm](https://www.jetbrains.com/pycharm/). We will use this to edit our project files.

## Jupyter Notebook

For the lectures, we will use Jupyter Notebooks, which provide an interactive way of learning Python and completing exercises. Jupyter Notebook files have the extension `.ipynb`.

1. To start, open your computer's default command line tool (Terminal for Mac, or PowerShell for Windows). Type `jupyter notebook` and press `Enter`. 
2. A webpage showing your computer's file directory should open automatically in your browser. Navigate to your Notebook file, and click.
3. Follow the steps [here](https://www.dataquest.io/blog/jupyter-notebook-tutorial/) to edit and use the contents of the Notebook file.

