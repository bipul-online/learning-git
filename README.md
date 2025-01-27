# Learning Git

## Git Workflow
- Working tree > Locally modified changes
- Index (stage area) > Staged changes
- Repository > Committed changes

## Utility Commands
- Show commit history `git log`
- View all branches `git branch -va`

## Working with Local
- Create repository: `git init`
- Check status: `git status`
- Add file: `git add <file>`
- Commit file: `git commit -m "<message>" <file>`
- Restore file: `git restore <file>`
- Check diff: `git diff`

## Working with Remote
- Add remote `git remote add origin https://github.com/bkumar2/learning-git.git`
- Verify remote URL `git remote -v`
- Fetch remote `git fetch`
- Set upstream `git branch --set-upstream-to=origin/
- Push to remote `git push <remote-name> <branch-name>`
master master`
- Merge upstream `git merge`

## Using Branches
- Create branch `git branch <branch-name>`
- Switch branch `git checkout <branch-name>`
- Merge branch `git merge <branch-to-merge>`
- Rebase branch `git rebase master`

## Reverting Changes
- Remove untracked files `git clean -f`
- Remove unstaged tracked files `git checkout .`
- Restore staged files to working tree `git restore --staged .`
- Remove staged files and working tree changes `git reset --hard`
- Stash staged files and working tree changes `git stash -u`
- Get stashed changes back `git stash pop`
- Reset local commit with remote commit `git reset --hard origin/master`
- Revert back to a version `git revert <commit-hash>`
- Hard reset to a version `git reset --hard <commit-hash>`

## Working with Fork
### Committer
- Click fork on github
- Clone repository `git clone <fork-url>`
- Add original repo as upstream `git remote add upstream <original-repo-url>`
- Get all changes from upstream `git fetch upstream`
- Merge upstream changes `git merge upstream/master`
### Reviewer
- 
