    # rebase interactivley
    git rebase -i
    
    # bring current branch to match remote
    git reset --hard origin/master
    
    # Cherry Picking commit from another branch
    # 1. create cherry pick branch based on 
    # 2. Cherry pick all needed commits
    # 3. commit
    
    
    git checkout -b cherry-pick-branch
    git cherry-pick sha
    git commit -m ""
    
    
    # print log on one line with
    git log --pretty=oneline
