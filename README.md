# git commands
#### configuration   
git config -l---> show config list  
git config help --->show all config   
git config --global user.email---> git config  
git config --global user.email "esraa@gmail.com"----> set config  
git config --global --unset user.email ---> delete config   
git config --global --edit  ---> open in  editor  
#### to generate security key 
ssh-keygen -t rsa-b 2022 -c "esraatarakhan@gmail.com" error
#### to push and pull 
git init  
git branch -c seconduplad//create new branch

get branch  //show my the current branch
get remote -v  
git add index.html  ||  git add *  
 git checkout seconduplad//switch to secondypload branch

get reset head index.html  ---> to unstage  
git commit -m "    "  
git remote add origin "http.....  
git push -u origin (master)//change master to  any branch name  

git pull origin 

#### alias
git status   -> git  st  
git config --global alias.st status  
git config --global alias.st  
@@@@@@@  
git branch   -> git  br 
git config --global alias.st branch    
@@@@@@@@@@@@@@  
git commit -m   -> git  cm  
git config --global alias.cm "commit -m"   
@@@@@@@@@@@@@@  
git config --global --edit   -> to open editor  
*git alias list on google searsh *   
#### branches   
git branch (show me branches)  
git branch scroll (create  branch named scroll)  
git checkout scroll(switched to branch "scroll")  
git branch -d scroll (to delete scroll branch)  (d is better than D)  
git branch -D scroll (force delete scroll branch even if there are editing)  
git checkout CHECKOUT -B Dev-feature (create branch and switch to it)    
git branch -m Development (to rename branch)  
Example 1:  
git checkout master (go to master)  
git merge Development (merge development with master)  
git push origin master ( push without pull request)  
git branch -d Development (delete Development branch)    

Example 2:  
git checkout Scroll (go to master)  
git push origin Scroll ( push with pull request)  

#### to push any thing you must pull latest updates from github  
#### stash files  
touch about.html  
ls  
git status  
echo "hello world" > about.txt  
git add *  
git status  
git stash   
git status   
ls  
git stash list  
git stash pop (to return stashed files)  
git stash list ( return empty list)  

















