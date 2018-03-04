gurubaran@gurubaran:~/Desktop/haanji$ git init
Initialized empty Git repository in /home/gurubaran/Desktop/haanji/.git/
gurubaran@gurubaran:~/Desktop/haanji$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
gurubaran@gurubaran:~/Desktop/haanji$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.txt

nothing added to commit but untracked files present (use "git add" to track)
gurubaran@gurubaran:~/Desktop/haanji$ git add -A
gurubaran@gurubaran:~/Desktop/haanji$ git log
fatal: your current branch 'master' does not have any commits yet
gurubaran@gurubaran:~/Desktop/haanji$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.txt

gurubaran@gurubaran:~/Desktop/haanji$ git commit -m "first commit"
[master (root-commit) 9d1edf4] first commit
 1 file changed, 69 insertions(+)
 create mode 100644 README.txt
gurubaran@gurubaran:~/Desktop/haanji$ git log
commit 9d1edf4aadaeaf490961cb05a9351eb5b0f3dc50 (HEAD -> master)
Author: mareaswa <emm.cit@gmailcom>
Date:   Sun Mar 4 23:19:06 2018 +0530

    first commit
gurubaran@gurubaran:~/Desktop/haanji$ git status
On branch master
nothing to commit, working tree clean
gurubaran@gurubaran:~/Desktop/haanji$ git status
On branch master
nothing to commit, working tree clean
gurubaran@gurubaran:~/Desktop/haanji$ git remote -v
gurubaran@gurubaran:~/Desktop/haanji$ git remote add origin https://github.com/mareaswa/haanj.git
gurubaran@gurubaran:~/Desktop/haanji$ git remote -v
origin	https://github.com/mareaswa/haanj.git (fetch)
origin	https://github.com/mareaswa/haanj.git (push)
gurubaran@gurubaran:~/Desktop/haanji$ git push -u origin master
Username for 'https://github.com': mareaswa
Password for 'https://mareaswa@github.com': 
remote: Repository not found.
fatal: repository 'https://github.com/mareaswa/haanj.git/' not found
gurubaran@gurubaran:~/Desktop/haanji$ git remote rm origin
gurubaran@gurubaran:~/Desktop/haanji$ git remote -v
gurubaran@gurubaran:~/Desktop/haanji$ git remote add origin https://github.com/mareaswa/haanji.git
gurubaran@gurubaran:~/Desktop/haanji$ git remote -v
origin	https://github.com/mareaswa/haanji.git (fetch)
origin	https://github.com/mareaswa/haanji.git (push)
gurubaran@gurubaran:~/Desktop/haanji$ git push -u origin master
Username for 'https://github.com': mareaswa
Password for 'https://mareaswa@github.com': 
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.06 KiB | 1.06 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/mareaswa/haanji.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
gurubaran@gurubaran:~/Desktop/haanji$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
gurubaran@gurubaran:~/Desktop/haanji$ ^C
gurubaran@gurubaran:~/Desktop/haanji$ 

