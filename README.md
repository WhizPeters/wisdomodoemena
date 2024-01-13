# wisdomodoemena
learning of backend

## Explain version control.
Version control is a system that records changes to a file or a set of files over time so that you can recall specific versions later. It is a crucial tool used in software development, document management, and collaborative projects where multiple contributors are involved.

## Explain difference between git and github
Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories. In simple terms, you can use git without Github, but you cannot use GitHub without Git.

## List 3 other github alternatives
GitLab
Bitbucket
SourceForge
## Explain the difference between git fetch and git pull
The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.

## Explain in simple terms git rebase and the command for it
Using git rebase is equivalent to recreating the local branch based on the latest commit of the remote branch, and then reapplying the locally added commit. There are several specific ways to use it: Add specific options each time you execute the pull command: git pull — -rebase

## Explain in simple terms git cherry-pick and the command for it
Let's say you have two branches - feature-branch and main-branch. You want to bring a specific commit from feature-branch into main-branch.

Identify the commit hash of the specific commit on feature-branch:

git log Switch to the main-branch:

git checkout main-branch Cherry-pick the commit from feature-branch:

git cherry-pick <commit_hash> Now, the changes from that specific commit on feature-branch are applied to main-branch.

Remember, while cherry-picking can be a handy tool, it's essential to be cautious when using it, especially in collaborative projects, to avoid potential conflicts.
