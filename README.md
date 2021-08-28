# github-tutorial-repo


Github Hands-on Repo 



Revert all the commits and move to the specific commit

Link :  https://stackoverflow.com/questions/4114095/how-do-i-revert-a-git-repository-to-a-previous-commit



Commands:

git reset HEAD~1   -  reset the first commit only. Please add the required changes and push it to the remote branch to make the changes


git reset --hard commit_ID    -  go back to that commit ID and changes cannot be reverted. Please push the changes to the remote branch to make the changes




cherry-pick functionality

steps:

1. get the commit ID from the current branch
2. git cherry-pick commit ID
3. push the changes to the remote branch


Link - https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Need-to-git-cherry-pick-a-commit-Heres-an-example-how


cherry-pick a commit from another branch to main branch

steps:

1. checkout the feature branch
2. get the commit ID
3. checkout the main branch
4. git cherry-pick commit ID 
5. Push the changes to the remote branch


Link - https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-git-cherry-pick-from-another-branch-to-your-own

