 Daftar tugas / branch
 1. Tugas-git
 2. Tugas-html
 3. Tugas-css
 4. Tugas-js
 5. Tugas-midProject
 6. Tugas-php
 7. Tugas-finalProject

 Daftar perintah GiT

ASUS@Kristania MINGW64 ~/Documents
$ cd belajarGIT

ASUS@Kristania MINGW64 ~/Documents/belajarGIT
$ git branch Tugas-git

ASUS@Kristania MINGW64 ~/Documents/belajarGIT
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git b833d6d] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating cfb660b..b833d6d
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 303 bytes | 151.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kristaniabullu19/belajarGIT.git
   cfb660b..b833d6d  main -> main

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 8ec86e6] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-html)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating b833d6d..8ec86e6
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 117.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kristaniabullu19/belajarGIT.git
   b833d6d..8ec86e6  main -> main

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css fcd16e1] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 8ec86e6..fcd16e1
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 379 bytes | 189.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kristaniabullu19/belajarGIT.git
   8ec86e6..fcd16e1  main -> main

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-js)
$  touch Tugas-js.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt"
[Tugas-js 263e8b2] Menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating fcd16e1..263e8b2
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 103.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kristaniabullu19/belajarGIT.git
   fcd16e1..263e8b2  main -> main

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject 68fd92d] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating 263e8b2..68fd92d
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 169.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kristaniabullu19/belajarGIT.git
   263e8b2..68fd92d  main -> main

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 5fce342] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating 68fd92d..5fce342
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 104.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kristaniabullu19/belajarGIT.git
   68fd92d..5fce342  main -> main

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject 11e007a] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 5fce342..11e007a
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@Kristania MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 332 bytes | 166.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kristaniabullu19/belajarGIT.git
   5fce342..11e007a  main -> main
