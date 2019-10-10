Update old git commit messages
===

reference: https://www.youtube.com/watch?v=ROl1wbQGHMk

### 1. For last commit message update
    > git log
    > git commit --amend
        VI editor will be opened then edit the commit message and save (wq)
    > git push -f

### 2. For older commit messages update
    > git log
    > git rebase -i HEAD~2
        VI editor will be opened then change "pick" to "reword" in all commit message that you want to update
        save it
        Again VI editor will be opened for 1st commit message, edit the commit message then save and quit
        Again VI editor will be opened for 2nd commit message
        so on...
    > git push -f
