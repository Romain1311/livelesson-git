#New TitleChange&New TitleOtherChange

Title
git clone
git commit
New addition
git diff HEAD~1
git log
git restore --source hash file
	-restore the version of the file corresponding to the state with the hash
## TITLE2
git remote add origin url, define the link to a space with the name 'origin' with url
git pull
Closing

- git branch <NAME> create a branch
- git branch rm <NAME> remove branch
- git switch (-c) <NAME> move to branch (and create it on the fly)
- git merge <BRANCH> merge the current with <BRANCH>
	- Can be automatically combined
- git rebase <BRANCH> to call from the branch to be rebased
- git status to know what to do during merge or rebase
- git rebase --continue after fixing conflicts
- git add <file> after fixing conflicts in the code
- git rebase -i HASH or HEAD~4 to go interactive mode with squash or s to squash commit into previous one
- git stash instead of git commit to store changes without commit and change branch safely
	- stash is temporary
	- git stash apply to recover the last backup on a given branch
	- git stash clear to clear the stashes
- A merge on the remote is called a pull request or merge request
	- git push <where> <what>
- To update a PR, do changes locally and re push to the remote
- A merge conflict can happen after a PR is issued
- git fetch update git log
	-git fetch --prune to prune branches inexisting on the remote
- git push -f <where> <what> to force the push
<<<<<<< HEAD
	-git push --force-with-lease <where> <what> to push more carefully and not erase 

## Collaborators
- Second one to push need to sync their local with the remote repo
	- git push --force-with-lease <where> <what> to push more carefully and not erase
- Add a collaborator in the settings of the repo
	- The collaborator use git clone to get a copy of the remote on its local machine
- Each person's branch changes are independent from others

