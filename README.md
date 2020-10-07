# 2020-10-07-git_collab-joe
Git collaboration

Git clone https://github.com/gswamyx/2020-10-07-git_collab-joe.git
will clone this repository to my local machine under the directory of the same name 2020-10-07-git_collab-joe

- `git branch <NAME>`: creates a branch <NAME> where you currently are

- `git branch -a`: shows you all local and remote branches

- `git checkout <BRANCH>`: switch to the <BRANCH>`

- `git checkout -b <BRANCH>`: create and checkout <BRANCH> in one step

## Pull requests (online merge aka merge request)

- ` git log --oneline --graph --all`: shows you your git history tree
- ` git fetch --prune`: delete local references to deleted remote branches
- ` git fetch`: updates local references with remotes
- ` git branch -d <BRANCH>`: delete local <BRANCH>

## Conflicts

- update your branches (e.g `git checkout main`;`git pull origin main`)
- goto conflicting branch: git checkout <RBANCH>
- `git rebase main`: will rebase <BRANCH> against main
