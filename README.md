# belajarGIT

Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
...
HP@LAPTOP-7AKQ53SQ MINGW64 ~ (master)
$ git config --global user.email "catherineassa26@gmail.com"

HP@LAPTOP-7AKQ53SQ MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/HP/.git/

HP@LAPTOP-7AKQ53SQ MINGW64 ~ (master)
$ cd C:\GIT

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT
$ git clone https://github.com/Catherine263/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT
$ cd belajarGIT

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-git

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-git
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-git f12b661] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
On branch Tugas-git
nothing to commit, working tree clean

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ ^C

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit --amend -m "Menambahkan file Tugas-git.txt"
[Tugas-git 094765b] Menambahkan file Tugas-git.txt
 Date: Tue Mar 12 00:33:48 2024 +0800
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan pada Tugas-git.txt"
[Tugas-git 8a086b3] Menambahkan perubahan pada Tugas-git.txt
 1 file changed, 1 insertion(+)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating a98436c..8a086b3
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 603 bytes | 301.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Catherine263/belajarGIT.git
   a98436c..8a086b3  main -> main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-git
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-html

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html e70c071] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[Tugas-html f7a1877] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating 8a086b3..f7a1877
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 582 bytes | 291.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Catherine263/belajarGIT.git
   8a086b3..f7a1877  main -> main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-css

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 69ff527] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[Tugas-css aa4269f] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating f7a1877..aa4269f
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 612 bytes | 306.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Catherine263/belajarGIT.git
   f7a1877..aa4269f  main -> main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-js

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js d09b8fa] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[Tugas-js 6d30bc2] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating aa4269f..6d30bc2
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 559 bytes | 559.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Catherine263/belajarGIT.git
   aa4269f..6d30bc2  main -> main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-midProject

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 84016aa] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
[Tugas-midProject bbfbf9e] Menambahkan perubahan pada Tugas-midProject.txt
 1 file changed, 1 insertion(+)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 6d30bc2..bbfbf9e
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 574 bytes | 287.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Catherine263/belajarGIT.git
   6d30bc2..bbfbf9e  main -> main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-php

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 235a442] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[Tugas-php 6b74cae] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating bbfbf9e..6b74cae
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 548 bytes | 548.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Catherine263/belajarGIT.git
   bbfbf9e..6b74cae  main -> main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject^C

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git rm Tugas-finalProject
error: the following file has changes staged in the index:
    Tugas-finalProject
(use --cached to keep the file, or -f to force removal)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "commit"
[Tugas-finalProject 1fc45ca] commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ del Tugas-finalProject
bash: del: command not found

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git rm Tugas-finalProject
rm 'Tugas-finalProject'

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "menghapus Tugas-finalProject karena salah tipe file"
[Tugas-finalProject a6122d4] menghapus Tugas-finalProject karena salah tipe file
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 Tugas-finalProject

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject deedaf6] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[Tugas-finalProject 995c70c] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProjeck
merge: Tugas-finalProjeck - not something we can merge

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 6b74cae..995c70c
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 2 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (9/9), 933 bytes | 466.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/Catherine263/belajarGIT.git
   6b74cae..995c70c  main -> main

HP@LAPTOP-7AKQ53SQ MINGW64 /c/GIT/belajarGIT (main)
$
