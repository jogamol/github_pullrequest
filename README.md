# github_pullrequest


https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

add this command if have this error Could not open a connection to your authentication agent.
eval `ssh-agent -s`


This is to add current ssh to git bash

ssh-add ~/.ssh/id_rsa


--To make pull request


fetch master branch

git pull origin 

--> make necessary changes in files

git checkout -b new-branch    (to make newbranch and checkout at the same time)


git add -A  (to add all files which has been changed)

git commit -m "Fixed documentation typos"

git push --set-upstream origin new-branch


Then on GIthub UI you can make pull request




To delete branch 

git branch -d the_local_branch

git push origin --delete the_remote_branch

