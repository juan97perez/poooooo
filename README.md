CarpetaCasa


# poooooo

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git init
Reinitialized existing Git repository in C:/Users/Juanma/Desktop/CarpetaCasa/poooooo/.git/

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   equipos.html
        modified:   index.html
        modified:   mi equipo.html
        modified:   partidos.html

no changes added to commit (use "git add" and/or "git commit -a")

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git add *

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   equipos.html
        modified:   index.html
        modified:   mi equipo.html
        modified:   partidos.html


Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git commit -m "parte1"
[master 4ed2194] parte1
 4 files changed, 4 insertions(+), 4 deletions(-)

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   equipos.html
        modified:   index.html
        modified:   mi equipo.html
        modified:   partidos.html

no changes added to commit (use "git add" and/or "git commit -a")

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git add *

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   equipos.html
        modified:   index.html
        modified:   mi equipo.html
        modified:   partidos.html


Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git commit -m "segunda parte"
[master 633c9b6] segunda parte
 4 files changed, 4 insertions(+), 4 deletions(-)

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$ git push origin master
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 659 bytes | 659.00 KiB/s, done.
Total 7 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 4 local objects.
To https://github.com/juan97perez/poooooo.git
   596cc96..633c9b6  master -> master

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/poooooo (master)
$
