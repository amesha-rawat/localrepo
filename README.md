#This is my local repo

<!-- branch commands -->

<!-- git branch -- to check branch -->

<!-- git branch -M main -- to rename a branch -->

<!-- git checkout <-branchname-> -- to nevigate go from one branch to another -->

<!-- git checkout -b <-newbranch-> -- this is used to create new branch-->

<!-- git branch -d <-branchname-> -- this is used to delete a branch 
but if we are already on a branch than we can't delete that branch-->

<!-- if we have more than one branch and we want the changes made in another branch to be showing on github just assume that our second branch is feature1 then this time we are going to be push like git push origin feature1 -->


<!-- 
Merging code(branch)
git diff <-branchname-> to compare commits,branches,files and more....to exit this just type q

git merge <-branchname-> to merge 2 branches this one is the first way of merging 

the other way of merging is on github by creating a PR which is a pull request
Pull Request - it lets you tell others about changes you've pushed to a branch in a repository on github
 -->

 <!-- 
 git pull origin main 
 it is used to fetch and download content from a remote repo and immediately update the local repo to match that content -->

 <!-- undoing changes
 
 case 1: staged changes (which are added but not commited)
        git reset<-filename->  if we want to reset a particular file
        git reset if we want to reset all the files

case 2: commited changes (for one commit)
        git reset HEAD~1 it means that the latest commit is default named as HEAD so it means reset the HEAD by 1

case 3: commited changes(for many commits)
        git reset <-commit hash->  hash is a code...each commit has it's own hash code and just to get this hash code we use git log command

        git reset --hard <-commit hash-> using hard will reset changes in vs code also           
  -->

  <!-- git log it is used to check all the commits -->