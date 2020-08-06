# PreWMAD-W1-d3
Repository to be forked by students as practice with git collaboration

## Assignemt 2: Partner Collaberation

Today you will be Learning a few new git techniques. We will be learning about forking, and cloning, and merging. 

A small guide of git commands you will be using 

git add .
git commit -m 'message'
git push -u origin master


git clone 
git pull



###Setup

step by step:

Student A: Fork this Repository

Student A: Clone your fork into a folder on your computer

Stduent A: Give collaborator access to your partner (in the settings of the repository, on github)

Student B: Clone developer A's Fork



###Adding to the files

Student A: Add some text to fileA.txt

Student A: add, commit, and push to github

Student B: pull the changes (git pull)

Student B: Make changes to fileB.txt

Student B: add, commit, push to github

Student A: Pull the changes (git pull)


Student A: make a change to fileC.txt

Student B: make a change to fileC.txt

Student A: add, commit, push changes to github. do this before student B.

Student B: add, commit, push changes (this will fail)

Student B: it will tell you there are changes you do not have. perform a git pull

From this point, it will tell you that there is a merge conflict, as you have made changes ot the same  file. you will have to resolve these conflicts, and then do a final git push. 

Student A: git pull
