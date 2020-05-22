1. git checkout develop; git pull
2. git checkout feature/branch-name
3. git rebase -i origin/develop
4. resolve all conflicts with the help of VS Code
5. git push origin feature/branch-name -f

more info:
  Resolve all conflicts manually, mark them as resolved with
  "git add/rm <conflicted_files>", then run "git rebase --continue".
  You can instead skip this commit: run "git rebase --skip".
  To abort and get back to the state before "git rebase", run "git rebase --abort".
