
+ how to fork on folder to here: 

```
git clone https://github.com/theleagueof/chunk
Create a branch using the git subtree command for the folder only

git subtree split --prefix=folder_name -b new_branch
Create a new github repo
Add this new repo as a remote,

git remote add upstream https://github.com/user/repo
Push the subtree

git push upstream new_branch
```
