# allotaxi-web

# Configuration .git/config

[core]
        repositoryformatversion = 0
        filemode = true
        bare = false
        logallrefupdates = true
[remote "origin"]
        url = https://github.com/lalmas-groupi/XXXX.git
        fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
        remote = origin
        merge = refs/heads/master


git remote add upstream https://github.com/lalmas-group/XXX.git
git pull upstream master


# Après git add et commit pour pousser sur votre remote re
git push --set-upstream origin feature
