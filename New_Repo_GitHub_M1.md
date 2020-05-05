PMuhuri\@CCASTA-HWJP0G2 MINGW64 /

\$ cd /c/GoT

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/GoT

\$ git init

Initialized empty Git repository in C:/GoT/.git/

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/GoT (master)

\$ git add –A

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/GoT (master)

\$ git commit -m "First Commit"

[master (root-commit) 0cb57e7] First Commit

4 files changed, 725 insertions(+)

create mode 100644 Git_Examples_RubyGarage.pdf

create mode 100644 Git_commands_mine.md

create mode 100644 Git_commands_refs.md

create mode 100644 History_Myfolder.txt

Before pushing I created a new repository called GoT, with a README.MD *file.*
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/GoT (master)

\$ git remote add origin <https://github.com/pkmedu/GoT.git>

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/GoT (master)

\$ git remote –v

origin https://github.com/pkmedu/GoT.git (fetch)

origin https://github.com/pkmedu/GoT.git (push)

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/GoT (master)

\$ git push origin master

To https://github.com/pkmedu/GoT.git

! [rejected] master -\> master (fetch first)

error: failed to push some refs to 'https://github.com/pkmedu/GoT.git'

hint: Updates were rejected because the remote contains work that you do

hint: not have locally. This is usually caused by another repository pushing

hint: to the same ref. You may want to first integrate the remote changes

hint: (e.g., 'git pull ...') before pushing again.

hint: See the 'Note about fast-forwards' in 'git push --help' for details.

\$ git pull origin master --allow-unrelated-histories

From https://github.com/pkmedu/GoT

\* branch master -\> FETCH_HEAD

Already up to date.

\$ git push --set-upstream origin master

Enumerating objects: 9, done.

Counting objects: 100% (9/9), done.

Delta compression using up to 4 threads

Compressing objects: 100% (8/8), done.

Writing objects: 100% (8/8), 734.45 KiB \| 23.69 MiB/s, done.

Total 8 (delta 1), reused 0 (delta 0)

remote: Resolving deltas: 100% (1/1), done.

To https://github.com/pkmedu/GoT.git

f4c360b..b7beb33 master -\> master

Branch 'master' set up to track remote branch 'master' from 'origin'.
