# Git-Command Cheatsheet
create a new repository :
> git init

clone :
> git clone <*URL*>

check status :
> git status

adding files to commit list :
> git add *

or

> git add <*filename*>

fetch :
> git fetch <*remote*>

commit :
> git commit -m "*message*"

amend commit :
> git commit -amend

push :
> git push <*remote*> <*branch*>

pull :
> git pull <*remote*> <*branch*>

merge :
> git merge <*branch*>

# Branches & Tags
list out all existing branches :
> git branch -av

create a new branch :
> git branch <*new-branch-name*>

delete branch :
> git branch -d <*branch-name*>

mark current commit with a tag :
git tag <*tag-name*>

# Commit History
log :
> git log

or 

> git log -p <*filename*>

check who changed what and when in <*filename*>
> git blame <*filename*>