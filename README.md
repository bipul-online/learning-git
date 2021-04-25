# Learning Git

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
- Push to remote `git push <remote-name> <branch-name>`
- Set upstream `git branch --set-upstream-to=origin/master master`
- 

## Branch
