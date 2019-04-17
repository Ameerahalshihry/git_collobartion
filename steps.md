### Team Leader
1. create repo
2. `git init` 
3. `git remote add <git url>`
4. `git add -A` then `git commit -m '<relevant message>'`
5. `git push origin master` push to repo master branch
6. `git checkout -b dev` to create dev branch and checkout to dev branch
7. run 4 - 5 again
8. `git push origin dev`
9. If you have a pull request



### Team mates
1. Fork and clone team leaders repo i.e. `git clone <your git repo url>`
2. run `git checkout -b dev` to create a dev branch
3. run `git remote add upstream <team leader git url>`
4. After you modify run `team leader #4` then `git push origin dev`
5. Send a pull request to team leader
6. after merge from team leader
7. run `git pull upstream dev` to get current version from team leader
