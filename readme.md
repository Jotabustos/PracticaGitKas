11) git reset --hard HEAD~1
12) git reset --hard 14926d1
13) git merge master ( Dice Already up-to-date ) Tiene sentido porque los cambios de master ya están en styled
19) git checkout styled
    git merge htmlify (conflicto)
    (resolvemos conflicto)
    git add git-nuestro.md
    git commit -m "Merge styled and htmlify"
21) git checkout master
    git merge styled

25) git log --graph
26) git merge --no-ff title
27) git reflog
    git reset 743793e
28) git reset --hard HEAD
29) git checkout master
    git branch -d title
30) git merge 00f4824 (merge FF)
32) git reflog
    git reset --hard 529e38f

33) git reflog
    git reset --hard 00f4824
