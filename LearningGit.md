1. create new branch main ->
git checkout -b main master
2. create new branch dev ->
git checkout -b dev main
3. delete branch master ->
git branch -d master
4. push changes to remote repo ->
git push -u origin dev
5. rename dev to develop ->
git branch -m "dev" "develop"
6. update new name branch remote ->
git push -u origin develop
git push origin -d dev
7. create branch experiment/git-merge ->
git checkout -b experiment/git-merge
8. change first string ->
nano README.md
9. commit
git add README.md
git commit -m "smth"
10. add string in the end of file ->
nano README.md
11. commit/push
git add README.md
git commit -m "smth"
git push -u origin experiment/git-merge
12. change branch to develop ->
git checkout develop
13. change first string README
nano README.md
14. add new string to end README
nano README.md
15. commit/push 
git add README.md
git commit -m "smth"
git push -u origin develop
16. pull request from experiment/git-merge to develop (merge request)
create pull request on github.com
17. conflicts
git pull origin develop
git checkout experiment/git-merge
git merge develop
nano README.md
git push -u origin experiment/git-merge
git add README
git commit -m "smth"
git push -u origin exp/git-merge

merge on github.com 
