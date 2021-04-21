#The git / github with examples:

##-The initial configuration: 

git config --global user.name "You" 

git config --global user.email you@you.com

git init

git config --global init.defailtBranch main 

git config --list 

nano ReadMe.md

##-Starting a project from zero or cloning an existing repository

cd..

cd..

mkdir folder1

cd folder1

git init 

nano readme.md (then write what you want)

 This is a test did by Steffan, enjoy it
 
 Ctrl+X & enter

git add readme.md 

git commit -m "namecommit"


##-Basic workflow commands to stage and commit

git clone steffan-debug@host:/path/to/repository

nano cellphone.js

 Script to accelarate the hub of the principal bar.

 Ctrl+X & enter

git add cellphone.js

git commit -m "barfix"

git push -u origin main 

git checkout -b cellphone 

git flow init

git flow feature start feature_branch 
##-Push to a remote repository

git init 

nano readme.md (then write what you want)
 
 Ctrl+X & enter

git add readme.md 
 
 This is a test did by Steffan, enjoy it

git commit -m "namecommit"

git branch -m main 

git remote add origin https://github.com/Steffan-debug/git1pro.git

nano programc.c

 Ctrl+X & enter

commit -m "head2"

git status  

git push -u origin main

##-Branches: create, delete, save/commit & merge 

git checkout mike

nano mike.py

 print('Hello, world!') ctrl + & y + enter

git add mike.py

git commit -m "commit1m"

git branch 

git log + q

git branch noe

git branch checkout noe

nano mike.py 

 print('Hello, world! I am here') 

 print('Are you afraid?)

 ctrl + & y + enter

git add mike.py 

git commit "commit1n"

git checkout mike

git merge noe

git log (verify the merge)

git pull 

git push

git checkout noe 

git push 

git push --set upstream origin noe 

git branch -b cabello

git branch checkout mike 

git branch -d cabello

##-Gitflow 

mkdir gitflow

cd mkdir

git flow init 

 main

 develop

 Confirm default options

 Check the gitflow directory and all done 

git branch =a 

 Check branches

git flow feature start freature_main

touch feature.html

git add .

git commit -m "commt1"

git reflog

git flow feature finish freature_main

git tag -1 

git flow release start '0.0.1'

touch fix.html
 
git add . 

git commit -m "fix0.0.1"

git flow release finish '0.0.1'

git tag -1


