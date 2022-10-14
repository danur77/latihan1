![Screenshot (1)](https://user-images.githubusercontent.com/115677839/195806437-fd1fd990-8112-4964-be0c-bf53c233cdab.png)
# latihan1

Andri@LAPTOP-L5A341BJ MINGW64 ~
$ pwd
/c/Users/Andri

Andri@LAPTOP-L5A341BJ MINGW64 ~
$ mkdir lab_pemrograman

Andri@LAPTOP-L5A341BJ MINGW64 ~
$ cd lab_pemrograman/

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman
$ mkdir latihan1/

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman
$ cd latihan1/

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1
$ git init
Initialized empty Git repository in C:/Users/Andri/lab_pemrograman/latihan1/.git/

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ echo "#latihan1" >> README.md

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ ls -l
total 1
-rw-r--r-- 1 Andri 197121 10 Oct 14 15:34 README.md

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git commit -m "danang nurcahyo"
[master (root-commit) f482642] danang nurcahyo
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git config --global user.name "danur77"

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git config --global user.email "danangpaten1@gmail.com"

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git add origin https
fatal: pathspec 'origin' did not match any files

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git remote add github https://github.com/danur77/latihan1.git

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u master
fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u github master


Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git remote add origin https://github.com/danur77/latihan1.git

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 222 bytes | 111.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/danur77/latihan1/pull/new/master
remote:
To https://github.com/danur77/latihan1.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Andri@LAPTOP-L5A341BJ MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git clone https://github.com/danur77/latihan1.git
Cloning into 'latihan1'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
