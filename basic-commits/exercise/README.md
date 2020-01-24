2. What does git log look like?
$ git log
fatal: your current branch 'master' does not have any commits yet
--------------------------------------------------------------------------------------
4. What does the output from git status look like now?
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
--------------------------------------------------------------------------------------
6. How does git status look now?
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
--------------------------------------------------------------------------------------
8. How does git status look now?
$ git status
On branch master
nothing to commit, working tree clean
--------------------------------------------------------------------------------------
10. How does git status look now?
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
--------------------------------------------------------------------------------------
12. How does git status look now?
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
--------------------------------------------------------------------------------------
15. What does the status look like now? The log?
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
$ git log
commit cfe6fdf516694126184afae7b76ba8be33ebc272 (HEAD -> master)
Author: MantaRey <reymunme@uci.edu>
Date:   Fri Jan 24 03:28:37 2020 -0800

    Updated readme.md

commit b60647db420c7f0395e0f38b0a80c7caca71d92c
Author: MantaRey <reymunme@uci.edu>
Date:   Fri Jan 24 03:21:43 2020 -0800

    Added readme.md
--------------------------------------------------------------------------------------
