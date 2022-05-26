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

* __Merge of branches__ 
    1. Use command __git merge branch_name__. While doing that, one should be on a branch where you want those changes to be. 

* __Conflicts__
    1. Conflicts occur when there are contradictonary commits in branches
    2. There are 2 non-conflict strategies: __fast-forward__ and __ort__. Fast-forward merge happens when only 'daughter' branch was modified. Ort strategy happens when both branches were modified, but in different 'areas'. 
    3. When solving conflict the safest option is _accept both_

