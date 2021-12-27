# Repository for Activity 9.1


Commands used

(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git init
Initialized empty Git repository in /Users/faitusjelinejoseph/Documents/MIT/Module9/uploadtogit/.git/
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git add .
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   MIT.ipynb
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git commit -m "First commit"
[master (root-commit) fda1d85] First commit
 1 file changed, 61 insertions(+)
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git remote add origin git@github.com:faitusjelinej/PCDE-Activity-9.1.git
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 876 bytes | 876.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:faitusjelinej/PCDE-Activity-9.1.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git add .                                                               
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git status                                                              
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   .ipynb_checkpoints/MIT-checkpoint.ipynb
	modified:   MIT.ipynb

(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git commit -m "second commit"                                           
[master 725b5e8] second commit
 2 files changed, 63 insertions(+), 2 deletions(-)
 create mode 100644 .ipynb_checkpoints/MIT-checkpoint.ipynb
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git remote add origin git@github.com:faitusjelinej/PCDE-Activity-9.1.git
fatal: remote origin already exists.
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git push -u origin master                                               
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 1.08 KiB | 1.08 MiB/s, done.
Total 5 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To github.com:faitusjelinej/PCDE-Activity-9.1.git
   fda1d85..725b5e8  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % ls -lrt
total 8
-rw-r--r--@ 1 faitusjelinejoseph  staff  1632 Dec 27 13:54 MIT.ipynb
(base) faitusjelinejoseph@MacBook-Pro-2 uploadtogit % git remote add origin git@github.com:faitusjelinej/PCDE-Activity-9.1.git
