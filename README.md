# Learning Git

## Utility
- Check logs `git log`

## Workflow
- Repository > Committed
- Index (stage area) > Staged
- Working tree > Modified

## Local
- Create repository: `git init`
- Check status: `git status`
- Add file: `git add <file>`
- Commit file: `git commit -m "<message>" <file>`
- Restore file: `git restore <file>`
- Check diff: `git diff`

## Remote
- Add remote `git remote add origin https://github.com/bkumar2/learning-git.git`
- Verify remote URL `git remote -v`
- Fetch remote `git fetch`
- Set upstream `git branch --set-upstream-to=origin/
- Push to remote `git push <remote-name> <branch-name>`
master master`
- Merge upstream `git merge`

## Branch
- Create branch `git branch <branch-name>`
- Switch branch `git checkout <branch-name>`
- Merge branch `git merge <branch-to-merge>`

## Revert back
- Remove untracked files `git clean -f`
- Remove unstaged tracked files `git checkout .`
- Restore staged files to working tree `git restore --staged .`
- Remove staged files and working tree changes `git reset --hard`
- Stash staged files and working tree changes `git stash -u`
- Get stashed changes back `git stash pop`
- Reset local commit with remote commit `git reset --hard origin/master`
- Revert back to a version `git revert <commit-hash>`