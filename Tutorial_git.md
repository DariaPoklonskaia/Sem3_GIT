# Git Tutorial

*git init* - команда для инициализации git в папке, для начала отслеживания

*--help* - к любой команде для вызова справке, например git commit --help

*git commit --amend -m"new message"* - исправить сообщение предыдущего коммита

*git checkout master* - вернутся в ветку мастер

#Seminar 2
* __create new branch and switch b/w them__
1. To creane new branch use command **git branch branch_name**; where branch_name should be in one world
2. To switch between branches use **git checkout create_branch**. To switch to master branch use **git checkout master**
3. To check on whant branch you are use **git branch**

* __Merge of branches__ 
    1. Use command __git merge branch_name__. While doing that,one should be on a branch where you want those changes to be. 
* __Conflicts and solutions__

    1. Fast-forward merge means master was not modified and 'daughter' branch was modified
* __Seminar summary__