git commands

init: run only once
status: your friend

These are the commands to start out

git config --global user.name "Nick Murphy"
git config --global user.email "namurphy@cfa.harvard.edu"
git config --global color.ui "auto"
git config --global core.editor "emacs"

Can check with 

git config --list

git commit -m "created a readme for this repository"

To add everything:

git add . 

emacs .gitignore

Strategy: ignore results folder because they should be reproducible by code

git log
git log --oneline

