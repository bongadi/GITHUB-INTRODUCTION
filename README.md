# GITHUB-INTRODUCTION

# GitHub

This is a popular website for hosting and sharing  _Git_ repositories remotely.
GitHub is used with various developers as means to colaborate remotely. In this course you will learn the basic of GitHub.

**Objectives**
1. Inroduction to Repositories, branches , Pull requests and Forking
2. You will make a short Markdown file (profile.md) that you can use as your Profile ReadMe.


**Prerequisites**

Create a GitHub account [Join GitHub](https://github.com/join)

A GitHub account is made up of several key parts that help users manage and collaborate on projects. Here are the main parts:

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

A repository/repo contains all your project's files and each file's revision history. You can manage your project within its repo. Repositories can be personally owned or shared 
by different people in an organisation (collaboration). More on repositories can be found here [More on Repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)

 * To create a new repo you can simply click on ``NEW`` on the github window.
 *  Name your Repo
 *  You can put a brief desciption of your repo (optional)
 *  You can select if your repo is Public or Private
 *  Click on  _Intialize this Repo with a README file_
 *  Choose you a license (optional)- This tells others what they can and can't do with your code
 *  Click on ``Create repository``

   _Your first repo_ **CONGRATULATIONS!!** :+1:



   ### GitHub Branches

   A branch is parallel versions of your repo, by default you repo has one branch ``main`` and just like the name suggests this is your main/definitive/default branch.
   It is advisible to create additional copies of your `main` branch and make changes of it without actually affecting the core/default/main branch and ultimately your main
   project. (In other words in the case where different people are collaborating on one project branches ensures that everyones work is safe before any more changes are done on the main branch/projcet.)

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

#### Open a pull request

Collaboration happens on a pull request. The pull request shows the changes in your branch to other people and allows people to accept, reject or suggest additional changes to your branch. This pull request is going to keep changes you made on your branch and propose them to the `main` branch. For more on pull requests kinldy refer to 
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

A fork is a new repo that shares code and visibility with the original 'upstream' repo. For example you can fork a repo to propose changes to the main repo and submit a pull request when done. More on forks can be found here [Forking info](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks)
In this tutorial we will use the following github repo [octate/Spoon-Knife](https://github.com/octocat/Spoon-Knife)

1. Navigate to the github page listed above and click on `Fork`
2. Selcect the owner for the forked repo
3. You can put a brief description about the repo
4. Click  **Create Fork**
   [Detailed instructions on Forkinh](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
   

**SBB611 INTRODUCTION TO GIT HUB DONE** 🎊🎊


# Markdown Syntax

[Markdown Tutorial](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Practice markdown [here](https://www.markdowntutorial.com/)


