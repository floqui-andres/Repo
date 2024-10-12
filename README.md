# Headline


So, I forgot to use the ctrl + enter to save the code in VSCode, that is why I can not push the updates in my files


## Headline

Now I am updating this and that, learning to pull things and to push.

So if I'm using in VSCode I need to get the uatosave ON or keep pressing the ctrl + enter to get git noting the changes in my files.
So connecting with SSH allow me to not need to give the info after every required permission of modification, "the git know who am I and where am I modifing"

So for a new Repo in my machibe I need to:
1. git init in my folder
2. git add .
3. git commit -m "mesage"
4. git remote add origin "ssh copy code" (after being created the ssh key)
5. git branch -M main
6. git push -u main
7. git pull
8. Optionally I could stay in my folder on my local machine, and then after being init'ed and SSH'ed I will use git clone "the SSH link" of the repo that i want to download to my folder.


Now some other tools:
1. git help "command" to get the file of info related to this command
2.  To generate the SSH key I will use in Git Bash the next command: ssh-keygen -t rsa -b 4096 -C "theemailusedin@thegithubaccount.com"
3.  git checkout to change between branches
4.  git checkout -b "name of the branch" to create a new brach
5.  git branch to see what are the branches and I'm working in the * branch
6.  git branch -d "name of the branch" to delete that branch
7.  when a file is already added and I modified, then I can use git commit am "" to add and commit in the same step
8.  git log to see all the commits that I had done
9.  git reset "the code of the commit" to unstage until that commit
10.  git reset HEAD to unstage the last commit
11.  git reset HEAD~1 to unstage the 2 last commits
12.  rm .git/index to delete all the files stages and getting all to the initial steps
13.  git reset --hard to no only unstage but actually get the steps undone in my file
14.  Finally in the GitHub Fork is copy the repository to my profile and then I can edit that repo.
