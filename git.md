    # rebase interactivley
    git rebase -i
    
    # bring current branch to match remote
    git reset --hard origin/master
    
    # Cherry Picking commit from another branch
    # 1. checkout branch that you want to cherry pick to
    # 2. Cherry pick all needed commits
    
    git checkout production
    git cherry-pick sha
    
    
    # print log on one line with
    git log --pretty=oneline
