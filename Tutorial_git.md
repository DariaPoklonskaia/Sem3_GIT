# Git Tutorial

*git init* - команда для инициализации git в папке, для начала отслеживания

*--help* - к любой команде для вызова справке, например git commit --help

*git commit --amend -m"new message"* - исправить сообщение предыдущего коммита

*git checkout master* - вернутся в ветку мастер

## Seminar 2
* __create new branch and switch b/w them__
1. To create new branch use command **git branch branch_name**; where branch_name should be in one word
2. To switch between branches use **git checkout branch_name**. To switch to master branch use **git checkout master**
3. To check on what branch you are use **git branch**

* __Branches merge__ 
    1. Use command __git merge branch_name__. While doing that, one should be on a branch where you want those changes to be. 

* __Conflicts__
    1. Conflicts occur when there are contradictonary commits in branches
    2. There are 2 non-conflict strategies: __fast-forward__ and __ort__. Fast-forward merge happens when only 'daughter' branch was modified. Ort strategy happens when both branches were modified, but in different 'areas'. 

    In case of 'ort' strategy last commit will be x2 in the master log file. Also commit about merge will be added automatically. 
    3. When solving conflict the safest option is _accept both_

* __Deleting__

    1. To delete branch use command *git branch -d branch_name*. 
    2. *-d* allows to delete a branch when all modifications were copied and such delete would not cause any troubles. 

* __Misc (miscellaneous)__

Use *git diff* to see difference b/w edited and commited text files. 

Hash-code - commit file code

*Initial commit* - common message for first commit 

Master branch log would not show modifications, that were done in created from it branch (until branches merge). 

Use *.gitignore* file located in the same root folder to list all files you do not want to be tracked by git, and avoid annoying messages from git. This file should be commited. 

