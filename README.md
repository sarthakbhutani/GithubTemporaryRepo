# GithubTemporaryRepo
Temporary Repo


sarthak@LAPTOP MINGW64 ~
$ git clone https://github.com/sarthakbhutani/GithubTemporaryRepo.git -b master repo
Cloning into 'repo'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

sarthak@LAPTOP MINGW64 ~
$ ls
'3D Objects'/
 Anaconda3/
 ansel/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Dropbox/
 eclipse-workspace/
 Favorites/
 Links/
'Local Settings'@
 MicrosoftEdgeBackups/
 Music/
'My Documents'@
 NetHood@
 NTUSER.DAT
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 NTUSER.DAT{44be35cc-bddc-11e9-bd96-8091337dc7c8}.TxR.0.regtrans-ms
 NTUSER.DAT{44be35cc-bddc-11e9-bd96-8091337dc7c8}.TxR.1.regtrans-ms
 NTUSER.DAT{44be35cc-bddc-11e9-bd96-8091337dc7c8}.TxR.2.regtrans-ms
 NTUSER.DAT{44be35cc-bddc-11e9-bd96-8091337dc7c8}.TxR.blf
 NTUSER.DAT{44be35cd-bddc-11e9-bd96-8091337dc7c8}.TM.blf
 NTUSER.DAT{44be35cd-bddc-11e9-bd96-8091337dc7c8}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{44be35cd-bddc-11e9-bd96-8091337dc7c8}.TMContainer00000000000000000002.regtrans-ms
 ntuser.ini
 OneDrive/
 Pictures/
 Postman/
 PrintHood@
 Recent@
 repo/
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/

sarthak@LAPTOP MINGW64 ~
$ cd repo

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git add .


sarthak@LAPTOP MINGW64 ~/repo (master)
$

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt


sarthak@LAPTOP MINGW64 ~/repo (master)
$ git commit -m "first commit"
[master 6704628] first commit
 1 file changed, 7 insertions(+)
 create mode 100644 abc.txt

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git commit --amend --signoff
[master a47992b] first commit
 Date: Wed Oct 30 14:55:55 2019 +0530
 1 file changed, 7 insertions(+)
 create mode 100644 abc.txt

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git remote -v
origin  https://github.com/sarthakbhutani/GithubTemporaryRepo.git (fetch)
origin  https://github.com/sarthakbhutani/GithubTemporaryRepo.git (push)

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git fetch

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git push origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 422 bytes | 140.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/sarthakbhutani/GithubTemporaryRepo.git
   470cd06..a47992b  master -> master

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git remote add ra https://github.com/AmulyaX/android_device_xiaomi_lavender.git

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git remote -v
origin  https://github.com/sarthakbhutani/GithubTemporaryRepo.git (fetch)
origin  https://github.com/sarthakbhutani/GithubTemporaryRepo.git (push)
ra      https://github.com/AmulyaX/android_device_xiaomi_lavender.git (fetch)
ra      https://github.com/AmulyaX/android_device_xiaomi_lavender.git (push)

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        pqr.txt

nothing added to commit but untracked files present (use "git add" to track)

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git add pqr.txt

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   pqr.txt


sarthak@LAPTOP MINGW64 ~/repo (master)
$ git rm --cached pqr.txt
rm 'pqr.txt'

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        pqr.txt

nothing added to commit but untracked files present (use "git add" to track)

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git add .

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git restore --staged pqr.txt

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status'
>
> ^C

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        pqr.txt

nothing added to commit but untracked files present (use "git add" to track)

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git add .
git
sarthak@LAPTOP MINGW64 ~/repo (master)
$ git commit -m "2nd com"
[master 85e275a] 2nd com
 1 file changed, 1 insertion(+)
 create mode 100644 pqr.txt

sarthak@LAPTOP MINGW64 ~/repo (master)
$ git rebase -i HEAD~2
Successfully rebased and updated refs/heads/master.

sarthak@LAPTOP MINGW64 ~/repo (master)
$

