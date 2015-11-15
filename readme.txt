The use methods of git!

this dir is like a git-client, so don't mind git-server

- git status
  - git diff
  - git add "filename"
  - git commit -m "command"
- git status
##########update and see change -> sync change -> update and see change
->commite -> update and see change#############

git log (--pretty=oneline)   

git reset --hard HEAD-X (RESET)
git reset --hard commit_id
git reflog   see Branch log



workOcean  RegisterOcean Branch
the GIT DIFF is compare the workOcean and registerOcean
==> git diff HEAD -- readme.txt


git checkout --file    undo workOcean merge
git reset HEAD file    undo registerOcean merge


git rm file move       delete registerOcean file

ssh-keygen -t rsa -C "1780037398@qq.com"   create SSH KEY for SSH(e.g. GITHUB)  

continue with github:
git remote add origin(connect_name) git@github.com:lipengchengHust/git.git
git push -u origin master(first time)
git push origin master(second and later time)


All Rights Resovled by PhilLee
