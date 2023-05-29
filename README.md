
lfdc2@LAPTOP-AKOMHEJA MINGW32 ~
$ cd OneDrive

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive
$ cd Escritorio

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio
$ mkdir devjumpers

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio
$ git clone https://github.com/lfdc21/devjumpers.git
Cloning into 'devjumpers'...
warning: You appear to have cloned an empty repository.

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio
$ cd devjumpers

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ touch README.md

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ touch privado.txt

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ mkdir privada

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ touch .gitignore

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   privado.txt


lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git add privada

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   privado.txt


lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git commit -m"se crea el archivo privado.txt y la carpeta privada, aparte se ignora con .gitignore"
[main ac017c5] se crea el archivo privado.txt y la carpeta privada, aparte se ignora con .gitignore
 2 files changed, 2 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 privado.txt

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ touch 1.txt

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git checkout -b v0.2
Switched to a new branch 'v0.2'

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ touch 1.txt

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ touch 2.txt

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git commit -m"se crea rama y ficheros 1.txt y 2.txt"
[v0.2 ea84056] se crea rama y ficheros 1.txt y 2.txt
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git push -u origin v0.2
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 589 bytes | 294.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'v0.2' on GitHub by visiting:
remote:      https://github.com/lfdc21/devjumpers/pull/new/v0.2
remote:
To https://github.com/lfdc21/devjumpers.git
 * [new branch]      v0.2 -> v0.2
branch 'v0.2' set up to track 'origin/v0.2'.

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ checkout main
bash: checkout: command not found

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git merge v0.2
Updating ac017c5..ea84056
Fast-forward
 1.txt | 0
 2.txt | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/lfdc21/devjumpers.git
   351428c..ea84056  main -> main

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git commit -m"se pone texto en el archivo 1.txt"
[main 8ed1625] se pone texto en el archivo 1.txt
 1 file changed, 1 insertion(+)

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git checkout v0.2
Switched to branch 'v0.2'
Your branch is up to date with 'origin/v0.2'.

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git commit -m"se agrega texto al archivo 1.txt desde la rama"
[v0.2 4dd1c11] se agrega texto al archivo 1.txt desde la rama
 1 file changed, 1 insertion(+)

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git merge v0.2
Auto-merging 1.txt
CONFLICT (content): Merge conflict in 1.txt
Automatic merge failed; fix conflicts and then commit the result.

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main|MERGING)
$ git branch --merge
* main

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main|MERGING)
$ git branch --no-merge
  v0.2

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main|MERGING)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main|MERGING)
$ git add .

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main|MERGING)
$ git commit -m"se solucionan los conflictos"
[main 528e5a6] se solucionan los conflictos

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git merge
Already up to date.

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 807 bytes | 269.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/lfdc21/devjumpers.git
   ea84056..528e5a6  main -> main

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git branch -D v0.2
Deleted branch v0.2 (was 4dd1c11).

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git config --global alias.list "log --oneline --decorate --graph --all"

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git config --global alias.list "log --decorate --oneline --graph --all"

lfdc2@LAPTOP-AKOMHEJA MINGW32 ~/OneDrive/Escritorio/devjumpers (main)
$ git log --oneline --decorate --all --graph
*   528e5a6 (HEAD -> main, origin/main) se solucionan los conflictos
|\
| * 4dd1c11 se agrega texto al archivo 1.txt desde la rama
* | 8ed1625 se pone texto en el archivo 1.txt
|/
* ea84056 (origin/v0.2) se crea rama y ficheros 1.txt y 2.txt
* ac017c5 se crea el archivo privado.txt y la carpeta privada, aparte se ignora con .gitignore
* 351428c commit inicial

