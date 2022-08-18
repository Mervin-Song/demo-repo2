# Demo 2

some text

## git branch
if we type git branch into the terminal... we see * master
*= the branch you are on
master= the branch name

## git checkout 
if we type //git checkout -b feature-readme-instructions
We will get a notification "Switched to a new branch 'feature-readme-instructions'

if we type 'git checkout master' => we will switch to master branch.

In essence, git checkout -b creates new branch, git checkout switches branches

## git diff 'branch name'
Shows the different changes made to the code in the branch that is different from the master branch

## git push --set-upstream origin feature-readme-instructions

We can also type git push -u origin feature-readme-instructions.

Push to github and create a pull request
You will see this in the terminal
//remote: Create a pull request for 'feature-readme-instructions' on GitHub by visiting:
//remote: https://github.com/Mervin-Song/demo-repo2/pull/new/feature-readme-instructions

## git commit -am
Short cut for git add + git commit -m.
Only works on modified files and not newly created files

## git merge
to merge the branches together, usually the branched out one gets merged into master branch

## git reset
If a file went through git add .
Use this command to take the file out of staging

## git reset HEAD~1
The HEAD represent the last commit, so essentially it will undo the last commit made. 
Adding ~1 just ask git to go a step further from the last commit that we just made. 
E.g. git add . => git commit -m => git reset HEAD~1 will undo commit and undo add