## Git Branching

### Overview

Overview and cheat sheet of Git commands. Introduction to branching.

### Basic Commands
* 'git init' - Initialize local git repository
* 'git add' - Stage local working directory for commit
* 'git commit' - Commit staged files to local repository
* 'git status' - Show status of repository
* 'git rm --cached fileName' - Remove fileName from Commit
* 'git log' - show commit history
* 'git log --oneline' - Show commit history (compact)


### Remote repository Commands

* 'git remote add origin remoteRepoUrl' - Link local repo to 'remoteRepoUrl'
* 'git pull origin master' - Pull 'master' branch content from remote origin into current local branching
* 'git push origin master' - Push current local branch to 'master' branch of remote origin

### Branching Commands
* 'git branch' - List local branches, highlight check out branches
* 'git branch branchName' - Create branch 'branchName'
* 'git checkout branchName' - Move to branch 'branchName'
* 'git checkout -b newBranch' - Checkout branch 'newBranch', create it if needed.
* 'git push origin branchName' - Push local branch 'branchName' to origin
* 'git pull origin master' - Pull remote 'master' into local branch (resolve conflicts)
