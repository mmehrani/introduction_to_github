# Introduction_to_github
this is the repository which we will use for the workshop.

Holded workshops:
1 - Spring 2021: At scientific physics association of Sharif University of Technology. 

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

### Merge current branch to the main:
```
git merge
```
## Working in groups

## Conflicts