# Example Git Repository

We are learning to make commits.

Good Bye

# Create the repository locally
local repo -> "remote" repository; Use (git add remote <name> <URL>) where name is alias like "origin"

# Create the repo locally
git clone <URL>

# Create a branch locally
git checkout <branch> (Switch to branch)
git checkout -b <new branch name> (create and switch to branch)
git add ...; git commit -m "..." (several times for writing and commiting changes)
git push --set-upstream origin <new branch> (set-upstream will allow current local branch to track "new branch" in origin)
git pull [origin <new branch>] (if --set-upstream is executed, then git pull and git push is sufficient)

# Create a new branch remotely
using the Github UI to create <branch>
git fetch --all (fetches all branches that are sitting in origin but not available locally; we can also fetch individual branch as well)
git checkout <branch> (work locally now)
