git commit test;

some command below:
git init :creat a empty repository
git add : add file
git commit -m:commit to reposioty;m：comments
git log: show commit logs
git reset --hard HEAD^ ： back to last version, (^^ mean back two,too much use HEAD~100 etc)
git reflog :show every command
git checkout --<filename> : cancle modify
git reset HEAD <filename> :back to workspace
git rm <filename>: delete file
git remote add origin git@github.com:(githubname)/learngit.git ：Association origin git
git push -u origin master ；push to origin github first 
git push origin master:push to origin github
git clone git@github.com:<githubname>/<repositoryname>.git