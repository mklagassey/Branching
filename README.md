## Git Cheat Sheet

Adding to the otherBranch in order to practice branching stuff.

* 'git init' - Init a local git repo in your working directory
* 'git status' - Show state of local repo
* 'git log' - Shows what you've been up to
* 'git log --oneline' - Compact version
* 'git config -l' - Shows all the current settings

### Branching

* 'git branch' - shows local branches
* 'git branch newBranch' - literally creates a new branch called newBranch
* 'git checkout newBranch' - move to local branch newBranch
* 'git add .' - Stage current directory in git index
* 'git commit -m "message"' - Commits the staged changes to local repo
* 'git diffsha' - Shows differences between current commit and commit with id 'sha'
* 'git diff oneBranch otherBranch' - Shows differences between the two named branches


### Remote Repos

* 'git remote add alias url' - Adds an alias called "alias" for the remote repo at "url"
* 'git push alias aBranch' - Pushes local commits to repote repo "alias" branch called 'aBranch'
* 'git pull alias aBranch' - Like above but pulls into the local branch instead from alias' aBranch 
