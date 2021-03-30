# Introduction_to_github
this is the repository which we will use for the workshop.

#### Holded workshops:

- Spring 2021: At scientific physics association of Sharif University of Technology. 

# Git commands

## Crucial SSH key settings

Before starting Git we need to connect our local device to the [github](https://https://github.com/) account. please follow the two steps bellow:

- [Generating a new SSH key](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Adding a new SSH key to your GitHub account](https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

## Initial settings

For the only and first time let `git` know you!
```
git config --global user.name "Your Name"
git config --global user.email "yourmail@host.com"
```
Call `git` to start his collaboration at your repository:
```
git init
```
Get your in-cloud project at your local computer:
```
git clone <project_address>
```

## Developing the project
#### Out of curiosity check what files have been changed:
```
git status
```
#### The files how different is the file to its previous one:
```
git diff <filename.py>
```
#### Put your contributions on the stage. Ready to be launched!
```
git add <filename.py>
```

#### Two ways to express your contribution:
```
git commit
git commit -m "Minor Bug fixed!"
```
#### Send your contributions to the cloud:
```
git push
```
## Reverting a file to its previous commit:
Find the `commit ID` of that previous one. Indicate the path of the file which you mean `path/to/file`. Then call `git` to revert it:
```
git checkout [commit ID] -- path/to/file
```
you may find [This page](https://dev.to/lofiandcode/git-and-github-how-to-revert-a-single-file-dha) useful.
## Manage issues and ideas

#### Make a new branch to start your work on a copy of the project
```
git checkout -b <branch_name>
git checkout <branch_name>
```
*Note*: In case the branch existed, the `-b` should not be put.

#### Check how many local branches are open
```
git branch
```

### Merge one branch to the main:
Firstly checkout your branch to `main`. Being the branch `main`, use the command below
```
git merge <branch_name>
```
## Working in groups
#### It is important to always pull all the recent updates and then start your own one. to do so:
```
git pull
```
#### Put everyone task to his own branch to avoid conflicts. Use branching and merging turn by turn.
```
git checkout -b <branch_name>
git checkout <branch_name>
git merge
```
### Merge conflicts
Occurs in two cases:
- Somebody have made some changes to `your branch`
- You have changed some lines which have been also changed in `main` stream
