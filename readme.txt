git is a distributed version control system.
git is free software.
Git has a mutable index called stage.
Git tracks changes.
git.
giy 
[root@master GitTest]# vim hello.txt 
[root@master GitTest]# git status
On branch master
Your branch is up to date with 'origin/master'.
 
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   hello.txt
 
no changes added to commit (use "git add" and/or "git commit -a")
[root@master GitTest]# git restore hello.txt
[root@master GitTest]# git status
On branch master
Your branch is up to date with 'origin/master'.
 
nothing to commit, working tree clean