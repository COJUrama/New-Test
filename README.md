# New-Test

## 01. Version Control

According to [Git](https://docs.github.com/en/get-started/using-git/about-git), "a version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together". Version controls systems (VCS) are tools that help developers track, make, and manage changes to their software code. They also help developers store every change they make to a file at different stages so they and their teammates can retrieve those changes at a later time.

## 02. Differences between Git and GitHub

Git and GitHub are related concepts, but they share different purposes in the context of version control and collaboration. Git is a distributed version control system designed for tracking changes in a codebase over time and facilitating collaboration amongst programmers. Git also operates locally on your machine, allowing you to make changes, commit them, and maintain a complete history of your project.

GitHub, on the other hand, is a web-based platform that provides hosting for Git repositories. It serves as a collaborative layer on top of Git, enabling multiple developers to work together on a project. GitHub offers features such as issue tracking, pull requests, and other collaboration tools to enhance team coordination.

## 03. Three other alternatives

1. Bitbucket
2. GitLab
3. SourceForge

## 04. The difference between git fetch and git pull

`git fetch` and `git pull` are both commands in Git, but they serve different purposes. `git fetch` is a command in Git that retrieves changes from a remote repository, downloading any new changes, branches, or tags to your local machine. However, it is important to remember that after doing all of that, it does not automatically merge those changes into your working directory; it solely updates your local repository's view of the remote repository.

On the other hand, `git pull` is a combination of two actions: `git fetch` followed by `git merge`. It not only retrieves changes from the remote repository, similar to `git fetch`, but also automatically merges those changes into your current working branch.

THe choice between `git fetch` and `git pull` depends on whether you want to review changes before merging (`git fetch`) or if you want to update and merge in one step (`git pull`).

## 05. Git rebase and the command for it

In simple terms, `git rebase` is one of two great utilities designed to integrate changes from one branch onto another. The basic idea behind `git rebase` is to take the changes on one branch and apply them on top of another branch. This can be useful for incorporating the latest changes from a main branch into a feature branch.

### The command to perform a rebase:

```
git rebase <branch-name>
```

This command tells Git take the changes on the current branch and apply them on top of the specified branch (`<branch name>`).

## 06. Git cherry-pick and the command for it

In simple terms, `git cherry-pick` is a Git command that allows you to pick and apply a specific commit from one branch to another.

### Git cherry-pitch command

```
git cherry-pick <commit_hash>
```

This command tells Git to apply the changes introduced by the specified commit (`<commit_branch>`) onto your current branch.
