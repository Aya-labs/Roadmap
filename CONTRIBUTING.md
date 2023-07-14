# Ayalabs Roadmap Contribution Guide

Welcome to our project! We appreciate your interest in contributing to our roadmap using GitHub Issues. This guide will walk you through the process of making contributions and help you understand how to effectively collaborate with the community.

## Table of Contents

1. Getting Started
2. Creating an Issue
3. Contributing to Existing Issues
4. Issue Workflow
5. Closing an Issue
6. Code of Conduct

### Getting Started

Before you start contributing, make sure you have the following:

A GitHub account: If you don't have one, you can sign up for free at https://github.com/join.

Familiarity with the project: Take some time to explore the existing issues to get an understanding of the project's goals and roadmap.

Read the README: It contains important information about the project, including installation instructions, development guidelines, and contribution guidelines.

### Creating an Issue

If you have an idea, suggestion, or a bug report related to the project roadmap, you can create an issue to start a discussion. Here's how you can do it:

Go to the project's repository on GitHub https://github.com/Aya-labs/roadmap

Click on the "Issues" tab near the top of the repository page.

Click on the green "New Issue" button.

Provide a descriptive title and detailed description for the issue, including any necessary context or examples.

Apply appropriate labels to the issue (e.g., enhancement, feature, bug, question) to help categorize it.

Click on the "Submit new issue" button to create the issue.

Congratulations! You have successfully created an issue. The community and maintainers will review it, provide feedback, and start discussions related to the issue.

### Contributing to Existing Issues

If you find an issue in the repository that you want to contribute to, follow these steps:

Read the issue description carefully, as well as any previous comments or discussions to understand the context.

If you have something valuable to add, click on the comment box at the bottom of the issue page and write your comment.

If you have a solution or suggestion, provide a clear and detailed explanation. You can also attach relevant examples or screenshots if necessary.

Engage in a constructive discussion with others in the comments section. Be respectful of others' opinions and provide helpful feedback.

If you believe you can address the issue yourself, you can fork the repository, create a new branch, make your changes, and submit a pull request. Refer to the project's contribution guidelines for more information on pull requests.

### Issue Workflow

To maintain an organized and efficient issue management process, we follow a standardized workflow:

Open: An issue is opened by a community member or maintainer and is awaiting review and discussion.

Triaged: A maintainer has reviewed the issue and added appropriate labels and milestones. This indicates that the issue is being actively considered.

In Progress: A contributor has been assigned to work on the issue and is actively working on it. If you wish to work on an issue, kindly request to be assigned to it.

Resolved: The issue has been addressed, either by the original contributor or someone else in the community.

### Closing an Issue

Once an issue has been resolved, it can be closed. Here's how:

If you have the necessary permissions, click on the "Close issue" button on the issue page.

If you don't have permissions to close the issue, you can add a comment indicating that the issue has been resolved and request a maintainer or project owner to close it.

Provide a summary of the resolution in the comment, explaining how the issue was addressed.

If applicable, reference any relevant commits, pull requests, or documentation that resolved the issue.

Once the issue is closed, it will be marked as resolved in the issue tracker, and it will be removed from the active issues list.

Remember, closing an issue does not mean the end of the discussion. If further questions or concerns arise, feel free to reopen the issue and continue the conversation.

# Contributing to other repositories in Ayalabs Organisation

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone git@github.com:this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git switch` command:

```
git switch -c your-new-branch-name
```

For example:

```
git switch -c add-alonzo-church
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app](https://firstcontributions.github.io/#social-share).

You could join our slack team if you need any help or have any questions. [Join slack team](https://join.slack.com/t/firstcontributors/shared_invite/zt-1n4y7xnk0-DnLVTaN6U9xLU79H5Hi62w).

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).

### Code of Conduct

When participating in discussions and contributing to the project roadmap, we kindly ask you to adhere to our Code of Conduct. The Code of Conduct outlines the expected behavior and ensures a safe and inclusive environment for all participants. It promotes respect, open-mindedness, and professionalism.

You can find our Code of Conduct in the repository's root directory or by visiting CODE_OF_CONDUCT.md.

Conclusion
Thank you for your interest in contributing to our project roadmap using GitHub Issues. Your contributions and feedback play a crucial role in shaping the future direction of the project. By following this guide, you can effectively collaborate with the community and help us achieve our shared goals.

Happy contributing!
