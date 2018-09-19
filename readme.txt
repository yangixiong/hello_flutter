git commit test;

some command below:
git init :creat a empty local repository
git add : add file
git commit -m:commit to reposioty;m：comments
git log: show commit logs
git reset --hard HEAD^ ： back to last version, (^^ mean back two,too much use HEAD~100 etc)
git reset --hard <commit id>:back to this commit 
git reflog :show every command
git checkout --<filename> : cancle modify
git reset HEAD <filename> :back to workspace
git rm <filename>: delete file
git remote add origin git@github.com:(githubname)/learngit.git ：Association origin git
git push -u origin master ；push to origin github first 
git push origin master:push to origin github
git clone git@github.com:<githubname>/<repositoryname>.git
git checkout -b dev ：creat and switch branch    === git branch dev git checkout dev 
git branch dev : creat branch
git checkout dev : swith branch 
git branch:view branch
git checkout <branchname>:swith to branch
git merge:Merge the specified branch content to the current branch
git branch -d <branchname>:delete branch
git stash:Hide workspace
git stash list:view worksite
git stash apply <stashname || null >:restore work don't remove stash
git stash pop:restore work and remove stash
git branch -D <branchname>:Forced deletion branch
git remote: view origin repository
git remote -v:view origin repository detail
git push origin <branchname>:push to branch
git checkout -b <branchname> origin/<branchname>:creat origin branch in local
git branch --set-upstream-to=origin/<branchname> <branchname>:Association origin branch
git pull:get from origin 
git tag <tagname>:add tag 
git tag :view tags
git show <tagname>:show tag detail
git tag <tagname> <commit id>:give command tag
git tag -a <tagname> -m <some comments> <commit id> : add tag with 
git tag -d <tagname> :delete tag
git push origin <tagname> :push a tag to origin
git push origin --tags:push some tags to origin
git push origin :refs/tags/<tagname>: delete a origin tag
