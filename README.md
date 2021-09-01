# Taller
Taller para desarrollo

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller
$ pwd
/d/Proyectos/GitTaller

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller
$ ls
config.js  index.html

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller
$ git init
Initialized empty Git repository in D:/Proyectos/GitTaller/.git/

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        config.js
        index.html

nothing added to commit but untracked files present (use "git add" to track)

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add config.js

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   config.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add index.html

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   config.js
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        style.css


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add style.css

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   config.js
        new file:   index.html
        new file:   style.css


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'merv_@LAPTOP-N5TRPFBC.(none)')

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git config --global user.email "mxmaciasm@gmail.com"

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git config --global user.name mxmaciasm

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   config.js
        new file:   index.html
        new file:   style.css


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git commit
[master (root-commit) 5e785d6] mi primer proyecto
 3 files changed, 13 insertions(+)
 create mode 100644 config.js
 create mode 100644 index.html
 create mode 100644 style.css

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git log
commit 5e785d6442d11495d11f34a9fd866ad1cc3dc104 (HEAD -> master)
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:49:45 2021 -0500

    mi primer proyecto

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ get status
bash: get: command not found

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git checkout -- index.html

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
nothing to commit, working tree clean

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git diff index.html
diff --git a/index.html b/index.html
index 56efbdb..93f0631 100644
--- a/index.html
+++ b/index.html
@@ -4,7 +4,7 @@
     <meta charset="UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
-    <title>Document</title>
+    <title>Segundo cambio</title>
 </head>
 <body>


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add index.html

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git commit
[master d15e202] Ahora el tiene otro titulo
 1 file changed, 1 insertion(+), 1 deletion(-)

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
nothing to commit, working tree clean

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git log
commit d15e202b1d005c841e432aeec9598b5a08975379 (HEAD -> master)
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:56:14 2021 -0500

    Ahora el tiene otro titulo

commit 5e785d6442d11495d11f34a9fd866ad1cc3dc104
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:49:45 2021 -0500

    mi primer proyecto

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git log
commit d15e202b1d005c841e432aeec9598b5a08975379 (HEAD -> master)
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:56:14 2021 -0500

    Ahora el tiene otro titulo

commit 5e785d6442d11495d11f34a9fd866ad1cc3dc104
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:49:45 2021 -0500

    mi primer proyecto

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        controladores/

nothing added to commit but untracked files present (use "git add" to track)

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add .gitignore

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        TextoNoIgnorado.txt


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git commit -m "He agregado un git ignore"
[master bd15372] He agregado un git ignore
 1 file changed, 1 insertion(+)
 create mode 100644 .gitignore

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        TextoNoIgnorado.txt

no changes added to commit (use "git add" and/or "git commit -a")

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add textoNoIgnorado.txt

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        TextoNoIgnorado.txt

no changes added to commit (use "git add" and/or "git commit -a")

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add TextoNoIgnorado.txt

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   TextoNoIgnorado.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git commit -m "He agregado un txt"
[master 52d23d1] He agregado un txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 TextoNoIgnorado.txt

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git add .gitignore

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   .gitignore


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git commit -m "He agregado un gitignore"
[master b28ac9b] He agregado un gitignore
 1 file changed, 3 insertions(+), 1 deletion(-)

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git status
On branch master
nothing to commit, working tree clean

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git branch
* master

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git branch login

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git branch
  login
* master

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git checkout login
Switched to branch 'login'

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git branch
* login
  master

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git status
On branch login
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        login/

nothing added to commit but untracked files present (use "git add" to track)

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git add .

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git statud
git: 'statud' is not a git command. See 'git --help'.

The most similar command is
        status

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git status
On branch login
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   login/login.html


merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git commit -m "version alternativa con un login"
[login 08ac524] version alternativa con un login
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 login/login.html

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git log
commit 08ac5248e6019fab10ea0e4357dbf43c2f30f5b7 (HEAD -> login)
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 22:22:52 2021 -0500

    version alternativa con un login

commit b28ac9b6a24ee681206b06ce16e7dbc429ad4fb9 (master)
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 22:19:43 2021 -0500

    He agregado un gitignore

commit 52d23d1927728819607f9456c91020841091d11b
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 22:18:42 2021 -0500

    He agregado un txt

commit bd153720e9daf05aa80878ed8ada94ac9669f445
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 22:12:03 2021 -0500

    He agregado un git ignore

commit d15e202b1d005c841e432aeec9598b5a08975379
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:56:14 2021 -0500

    Ahora el tiene otro titulo

commit 5e785d6442d11495d11f34a9fd866ad1cc3dc104
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:49:45 2021 -0500

    mi primer proyecto

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git branch
* login
  master

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (login)
$ git checkout master
Switched to branch 'master'

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git branch
  login
* master

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git log
commit b28ac9b6a24ee681206b06ce16e7dbc429ad4fb9 (HEAD -> master)
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 22:19:43 2021 -0500

    He agregado un gitignore

commit 52d23d1927728819607f9456c91020841091d11b
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 22:18:42 2021 -0500

    He agregado un txt

commit bd153720e9daf05aa80878ed8ada94ac9669f445
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 22:12:03 2021 -0500

    He agregado un git ignore

commit d15e202b1d005c841e432aeec9598b5a08975379
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:56:14 2021 -0500

    Ahora el tiene otro titulo

commit 5e785d6442d11495d11f34a9fd866ad1cc3dc104
Author: mxmaciasm <mxmaciasm@gmail.com>
Date:   Tue Aug 31 21:49:45 2021 -0500

    mi primer proyecto

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git remote add origin https://github.com/mxmaciasm/Taller.git

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/mxmaciasm/Taller.git'

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git remote add origin https://github.com/mxmaciasm/Taller.git
error: remote origin already exists.

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/mxmaciasm/Taller.git'

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (master)
$ git branch -M main

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (main)
$ git branch
  login
* main

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (main)
$ git push -u origin main



merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (main)
$

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (main)
$

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (main)
$ git push -u origin main

Excepci▒n no controlada: System.ComponentModel.Win32Exception: El identificador de la ventana no es v▒lido
   en MS.Win32.ManagedWndProcTracker.HookUpDefWindowProc(IntPtr hwnd)
   en MS.Win32.ManagedWndProcTracker.OnAppDomainProcessExit()
   en MS.Internal.ShutDownListener.HandleShutDown(Object sender, EventArgs e)
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 8 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (16/16), 1.47 KiB | 755.00 KiB/s, done.
Total 16 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/mxmaciasm/Taller.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

merv_@LAPTOP-N5TRPFBC MINGW64 /d/Proyectos/GitTaller (main)
$
