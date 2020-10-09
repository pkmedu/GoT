**Example – Git cloning**
Pradip Muhuri\@Lenovo-PC MINGW64 \~ (master)

\$ git clone <https://github.com/SAS-Class/LearnSAS.git>
The following is the output.
Cloning into 'LearnSAS'...

**Example – Renaming a file**
\$ git mv Ex_put_putlog.sas Ex_put_putlog34.sas

**Example – Deleting a file**
\$ git rm Git_Examples_RubyGarage.docx

\$ git rm -f SASPy_test.sas
rm 'Week2/SASPy_test.sas'

[Removing files/folders in
Git](https://www.jquery-az.com/remove-file-directory-git/)

git rm --cached file1.txt
git commit -m "remove file1.txt"

And to push changes to remote repo

git push origin branch_name

**Example Remove a directory from the local repo and the remote rep**
-   git rm -r Week12
-   git commit -m "Removed"
-   git push

**Deleting multiple files example**
Suppose, we have a folder name “del-demo” that contains five text files
(tst1.txt, tst2.txt tst3.txt tst4.txt tst5.txt). We want to remove three files
by the single command and upload the changes. This is how it can be done:

\$ git rm del-demo/tst2.txt del-demo/tst3.txt del-demo/tst4.txt

**The output should be:**
rm ‘del-demo/tst2.txt’
rm ‘del-demo/tst3.txt’
rm ‘del-demo/tst4.txt’

If you deleted a file from the working tree, then commit the deletion:
git commit -a -m "A file was deleted"
And push your commit upstream:
git push

Remove a file from index with git rm --cached before commit
===========================================================


PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/AnalyzeMEPS (master)
\$ git config --local core.autocrlf false
git config --global core.autocrlf false

But if your user and email is not yet setup, the above might ask to set those
up. In that case you run:

To know more, read here:  
<https://stackoverflow.com/questions/17628305/windows-git-warning-lf-will-be-replaced-by-crlf-is-that-warning-tail-backwar/38112001> 


You can verify it using following git command, that lists all ignored files:
git ls-files --others -i --exclude-standard

PMuhuri\@CCASTA-HWJP0G2 MINGW64 /c/AnalyzeMEPS (master)
\$ git remote set-url origin <https://github.com/pkmedu/AnalyzeMEPS>
