- Folder, Files and Branches

fnvallejos@CRG-C02-23-0055 MINGW64 ~ (main)
$ mkdir VALLEJOS_IT120_Act1

fnvallejos@CRG-C02-23-0055 MINGW64 ~ (main)
$ cd VALLEJOS_IT120_Act1

fnvallejos@CRG-C02-23-0055 MINGW64 ~ (main)
$ git config --global user.name "vallejosjoey471-cmyk"

fnvallejos@CRG-C02-23-0055 MINGW64 ~ (main)
$ git config --global user.email "vallejosjoey471@gmail.com"

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ touch Profile.txt

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ touch Education.txt

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ touch Background.txt

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ touch Readme.txt

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ touch Test.py

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git init
Initialized empty Git repository in C:/Users/fnvallejos/VALLEJOS_IT120_Act1/.git/

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Background.txt
        Education.txt
        Profile.txt
        Readme.txt
        Test.py

nothing added to commit but untracked files present (use "git add" to track)

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git add .

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Background.txt
        new file:   Education.txt
        new file:   Profile.txt
        new file:   Readme.txt
        new file:   Test.py


fnvallejos@CRG-C02-23-0055MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git commit -m "add 5 files"
[main (root-commit) 4ad659b] add 5 files
 5 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt
        modified:   Test.py

no changes added to commit (use "git add" and/or "git commit -a")

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git add .

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git commit -m "initial infos"
[main af7b2da] initial infos
 4 files changed, 14 insertions(+)

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git branch VALLEJOS_B1

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git branch VALLEJOS_B2

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git branch VALLEJOS_B3

fnvallejos@CRG-C02-23-0055MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git branch VALLEJOS_B4

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git branch
  VALLEJOS_B1
  VALLEJOS_B2
  VALLEJOS_B3
  VALLEJOS_B4
* main


- BRANCH 1 

fnvallejos@CRG-C02-23-0055MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git checkout VALLEJOS_B1
Switched to branch 'VALLEJOS_B1'

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B1)
$ git status
On branch VALLEJOS_B1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Profile.txt

no changes added to commit (use "git add" and/or "git commit -a")

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B1)
$ git add Profile.txt

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B1)
$ git commit -m "insert Profile infos"
[VALLEJOS_B1 ebe649b] insert Profile infos
 1 file changed, 7 insertions(+), 1 deletion(-)

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B1)
$ git status
On branch VALLEJOS_B1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B1)
$ git add Readme.txt

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B1)
$ git commit -m "insert Branch1 commands"
[VALLEJOS_B1 7f1b5ee] insert Branch1 commands
 1 file changed, 142 insertions(+)


 - BRANCH 2
 
fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (main)
$ git checkout VALLEJOS_B2
Switched to branch 'VALLEJOS_B2'

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B2)
$ git status
On branch VALLEJOS_B2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Education.txt

no changes added to commit (use "git add" and/or "git commit -a")

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B2)
$ git add Education.txt

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B2)
$ git commit -m "insert Education infos"
[VALLEJOS_B2 036b623] insert Education infos
 1 file changed, 4 insertions(+), 1 deletion(-)

fnvallejos@CRG-C02-23-0055 MINGW64 ~/VALLEJOS_IT120_Act1 (VALLEJOS_B2)
$ git checkout VALLEJOS_B1 -- Readme.txt

