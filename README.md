# Demo-Devops


git clone https://github.com/saran2250/Demo-Devops.git   (pulled global code to local)  ---- this is for the first time(only one time)

git status

git add  filenames  - it will add modified files to staging area

git commit -m "message"

git push
git config --global --edit
username
email
auth

git push                                       (pushed local code to github)

git pull                                       (pulls global code to local)


file modified --> git add(staging area) ---> git commit(only staged files)  ---> git push(only commited files can be pushed to global/github)

Git pull vs fetch

Git Fetch is the command that tells the local repository that there are changes available in the remote repository without bringing the changes into the local repository. Git Pull on the other hand brings the copy of the remote directory changes into the local repository.

Git branching

#create a new branch
git branch branchname

Git reset
git reset HEAD~1 (removes latest 1 commit from commit history, modes: soft, mixed, hard)

Git Checkout
git checkout commitID (revert to particular commit)
git checkout branchname (switch to particular branch)

Topics to be explored
======================
 git revert
 
 Git pull request


