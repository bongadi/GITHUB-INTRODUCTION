# GITHUB-INTRODUCTION

# GitHub

This is a popular website for hosting and sharing  _Git_ repositories remotely.
GitHub is used with various developers as means to collaborate remotely. 
Briefly you will learn the basics of GitHub.

**Objectives**
1. Introduction to Repositories, branches , Pull requests and Forking
2. You will make a short Markdown file (profile.md) that you can use as your Profile ReadMe.


**Prerequisites**

Create a GitHub account [Join GitHub](https://github.com/join)

A GitHub account is made up of several key parts that help users manage and collaborate on projects. 
Here are the main parts:

**1. Profile**

**Username:** This is your unique identity on GitHub.

**Bio:** A short description about yourself, your interests, or your expertise.

**Profile Picture:** An avatar or photo to represent yourself on GitHub.

**Pinned Repositories:** You can "pin" repositories on your profile to highlight the most important or relevant projects you're working on.

**Contributions Graph:** Shows your activity over time, such as commits, pull requests, and issues, giving an overview of how active you are on GitHub.

**2. Repositories (Repos)**

**Repository Name:** Each project has its own repository with a unique name.

**README.md:** This is a markdown file that provides an overview of the project, instructions, or any necessary documentation.

**Issues:** A system for tracking bugs, feature requests, or tasks related to the repository.

**Pull Requests:** Contributions made by users, suggesting changes to the code or files within the repository.

**Branches:** Different versions of a project, allowing multiple development streams (e.g., main, dev, or feature-specific branches).

**Releases:** Versions of the project that are marked as stable and can be downloaded.Releases: Versions of the project that are marked as stable and can be downloaded.

**Commits:** Individual changes made to the code or documentation, with a message explaining what was altered.

**Releases:** Versions of the project that are marked as stable and can be downloaded.
 
## Repositories 
A repository is a storage space where your project’s code, files, and history are stored.

It tracks all changes made to the files over time, allowing developers to collaborate, review the history, and restore previous versions.

You can think of it as the main project folder with all your files and the version history.

Repositories can be local (on your computer) or remote (on a platform like GitHub, GitLab, etc.).. More on repositories can be found here [More on Repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)

 * To create a new repo you can simply click on ``NEW`` on the github window.
 *  Name your Repo
 *  You can put a brief desciption of your repo (optional)
 *  You can select if your repo is Public or Private
 *  Click on  _Intialize this Repo with a README file_
 *  Choose you a license (optional)- This tells others what they can and can't do with your code
 *  Click on ``Create repository``

   _Your first repo_ **CONGRATULATIONS!!** :+1:



   ### GitHub Branches
   A branch is a version of the repository that diverges from the main working project.
   
   It allows you to work on features, bug fixes, or changes independently without affecting the main branch (often called master or main).
   
   Once your work on a branch is done, you can merge it back into the main branch.
   
   Example: You may create a new branch called feature-login to work on the login feature without disturbing the stable code on the main branch.

   By default the `main` branch is the base branch for new `pull requests` and code commits.

   **Making your first Branch**

   1. Navigate to the `< > Code` tab in the header menu of your repo
   2. Click on the `Main ` tab dropdown
   3. Enter the name you branch _My first-branch_
   4. Click **Create branch** This will automatically swith to the new branch you have created,the new branch name will also be reflected.

**Your First Branch, CONGRATULATIONS!!!** 🎉


### Committing a file 

Now that you have a file it is time to create your first file and make a commit.
A commit is the changes made to the folders and files in the branch of a particular project. Commits exist in a branch.
More on commits refer to [About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)

**Making your first commit**
1. Click on the `Add file` drop down click _Create new file_
2. In the name your file field type _profile.md_ 
   **note**: .md is an extension for a markdown file. More on Markdown can be found here; go through it to get a better understanding on Markdown files
   [More on Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
   and [Communication with Markdown](https://github.com/skills/communicate-using-markdown)
3. In the enetr file pane give a brief description of yourself as your profile (like two sentences)
4. Click `commit changes` in the upper right corner, you can then enter a brief description about your commit and `click Commit Changes`

   **First commit, CONGRATULATIONS** ✨ 

#### Pull Request (PR):
A pull request is a way to propose changes that you've made in one branch be merged into another branch (often the main branch).

It allows others to review your code before integrating it into the main repository.

PRs are commonly used in collaborative environments, where teams can discuss and provide feedback on changes before finalizing them.

Once a PR is approved and merged, the changes become part of the target branch.. For more on pull requests kinldy refer to 
[Info on Pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

![my-firstcommit](https://github.com/Natasha-Adongo/Bioinformatics-Training/assets/109069282/bcb3a422-10d3-4bdb-b10b-46ba08012148)

You will notice the pop-up message after your commit indicating your recent push to your branch providing a button that says *Comapare & Pull request*
To create a pull request you will:-
1. Click on Pull requests tab in the header menu of your repo
2. Click New Pull request
3. Base dropdown make sure main is selected
4. Select the compare dropdown and click my first branch
5. Click create pull request
6. Enter the name and description of your pull request
7. Click create pull request

**DONE!!!**  🎊

#### Forking

Forking is creating a copy of someone else’s repository under your account.

This allows you to make changes to the project without affecting the original repository

Forking is typically used when you want to contribute to someone else's project. After making changes in your forked repository, you can submit a pull request to the original project for review.

Example: You might fork an open-source project to add a new feature or fix a bug, then send a pull request back to the original repo. More on forks can be found here [Forking info](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks)

1. Navigate to the github page listed above and click on `Fork`
2. Selcect the owner for the forked repo
3. You can put a brief description about the repo
4. Click  **Create Fork**
   [Detailed instructions on Forkinh](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
   

**SBB611 INTRODUCTION TO GIT HUB DONE** 🎊🎊


# Markdown Syntax

[Markdown Tutorial](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Practice markdown [here](https://www.markdowntutorial.com/)


