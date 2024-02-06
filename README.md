$ git checkout -b iss53
Switched to a new branch "iss53"
$ git branch iss53
$ git checkout iss53
$ vim index.html
$ git commit -a -m 'Create new footer [issue 53]'
$ git checkout master
Switched to branch 'master'
 git checkout -b hotfix
Switched to a new branch 'hotfix'
$ vim index.html
$ git commit -a -m 'Fix broken email address'
[hotfix 1fb7853] Fix broken email address
$ git checkout master
$ git merge hotfix
