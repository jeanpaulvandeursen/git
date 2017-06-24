 # Git

 ## Sample git session with file renaming
~~~~
 git init
 vi oyeah.md
 git add *
 git status
 git commit * -m "initial"
 git status
 mv oyeah.md ono.md
 ls -al
 git status
 git checkout oyeah.md
 ls -al
 git status
 git rm --cached oyeah.md
 ls -al
 git status
 git add *
 git commit * -m "initial"
 ls -al
 git status
 git show
 git ls-files
 git mv ono.md omaybe.md
 git status
 git commit * -m "renamed ono to omaybe"
 git status
 git show
 ls -al
 git ls-files
 git status
 git commit
 git status
 ls -al
 git ls-files
 ~~~~