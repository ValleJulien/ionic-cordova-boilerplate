# git workflow:
    + a new branch :
        - `git checkout -b <feature-name>`
    + add all files changes :
        - `git add -A`
    + commit your changes :
        - `git commit -m "<your message to commit>"`
    + Save the feature/branch on your origin:
        - `git push origin <feature-name>`
    + If you work with fork and pull request, create a pull request on github or desktop app
    + When the pull request is validated and merged, delete the branch if you need from local and git server:
        - `git branch -d <feature-name>` and on the server: `git push origin --delete <feature-name>`
    + Update the fork or the origin :
        - `git pull upstream master && git push origin master`
    + Merge a branch with the updated master :
        - `git merge master`
------------------------------------------------------------------------------
