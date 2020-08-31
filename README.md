# git-workflow
default workflow for git

### basic workflow
```
# issue 'DEV-123' received
git checkout -b DEV-123
# work on your changes / push updates to your branch
git commit -am "added github readme for github branch workflow"
git push --set-upstream origin DEV-123
# pull in any changes from master / fix conflicts if any
git pull origin master
# commit and push again if there were changes in master
git commit -am "pulled in master"
git push
# go to pull request link displayed in console and create pull request
```