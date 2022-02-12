# LearnGit


## Basic git commands
    git switch -f <branch-name>
    
    git clone https://.git
    
    -- Overide local with remote as-is 
    git checkout -f uat
    git fetch origin uat
    git reset --hard origin/uat
    git clean -fdx
    git branch
    git status
    
    
    -- Overide local with remote and keeping Non-Committed files
    git checkout -f uat
    git fetch origin uat
    git reset --hard origin/uat
    git branch
    git status
    
    -- Committing the file to local
    git status
    git add *
    git commit -m "commit-0101"
    git status
    
    
    -- Push changes from local to remote
    git push -u origin uat
    
    -- Rollback last commit in remote (Get commit id for second last to which you want to rollback)
    git reset --hard 69f24ca6960b9065b6c5a663f9d198faa7dbe817
    git push --force origin uat
