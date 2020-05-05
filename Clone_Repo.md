\$ git clone https://github.com/pkmedu/TestRepo.git

Cloning into 'TestRepo'...

remote: Enumerating objects: 3, done.

remote: Counting objects: 100% (3/3), done.

remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0

Unpacking objects: 100% (3/3), done.

\$ git status

On branch master

Your branch is up to date with 'origin/master'.

Untracked files:

(use "git add \<file\>..." to include in what will be committed)

Clone_Repo.docx

Git_Examples_RubyGarage.pdf

Git_commands_mine.md

Git_commands_refs.md

History_Myfolder.txt

\~\$one_Repo.docx

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/TestRepo (master)

\$ git add -A

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/TestRepo (master)

\$ git commit - "First Commit"

error: pathspec '-' did not match any file(s) known to git

error: pathspec 'First Commit' did not match any file(s) known to git

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/TestRepo (master)

\$ git commit -m "First Commit"

[master 92d44a4] First Commit

6 files changed, 725 insertions(+)

create mode 100644 Clone_Repo.docx

create mode 100644 Git_Examples_RubyGarage.pdf

create mode 100644 Git_commands_mine.md

create mode 100644 Git_commands_refs.md

create mode 100644 History_Myfolder.txt

create mode 100644 \~\$one_Repo.docx

\$ git push

Enumerating objects: 9, done.

Counting objects: 100% (9/9), done.

Delta compression using up to 4 threads

Compressing objects: 100% (8/8), done.

Writing objects: 100% (8/8), 743.44 KiB \| 23.98 MiB/s, done.

Total 8 (delta 0), reused 0 (delta 0)

To https://github.com/pkmedu/TestRepo.git

0488b43..92d44a4 master -\> master
