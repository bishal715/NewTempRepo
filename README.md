git init
git add .
git commit -m "wsfr"
git remote add origin https://github.com/bishal715/NewTempRepo.git
git push origin main
git branch
git checkout -b <new branch name>
git branch -d <branch to be deleted 's name>
git checkout <jump to another branch name>
git reset . #undo the add operation
git reset HEAD~1 #get back to the previous commit
git reset <commit's hash>
git reset --hard <commit's hash removing the changes after this commit live in the code>
git merge <branch name> #merge two branches
git diff <branch name> #shows the differences between two branches