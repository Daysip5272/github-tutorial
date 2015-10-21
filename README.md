# GitHub Tutorial

_by <Daysi Patino>_

---
## Git vs. GitHub  
Git: 
 * version of control(snapshot of code)     
 * not required github       
 * runs in command line   
 * you have a directory (folder) of files once we initialize git (, we call it a repository (repo for short)     

Github:  
 * store in cloud        
 * visually changes  
 * easily collaborate on files   
 * github.com website   
 * runs in command line     
 * to interact with repositories & visually  see changes between commits  


---
## Initial Setup 

1. Sign Up on github.com
 * on top-right 
 * profile icon 
 * settings
 * left sidebar 
 * SSH keys
2. Go to c9.io open an account with github( a little cat on the top right coner)
 * create a workspace 
 * give it a name like (github-learning)and if you want a description
 * then press "Create Workspace"
 * before getting in the workspace you just made you have to get the SSH keys 
 * for that you have to be in the page that you go after sign in
 * look for the icon on top right (click it)
 * then look for the SSH Keys on the middle left (click it)
 * then copy the box that said default ssh keys
3. go back to github SSH Keys 
 * press the "Add SSH Key"
 * as tittle type c9
 * then paste the SSH Key that we copy from c9
 * the press "Add key
 * open the the workspace that you just made 
 * type "ssh -T git@github.com" if you see this "yourname@github-learning"then everything is alright
 #####(if you sign in on nitrout then do this if not then don`t)
 * then type "git config --global user.name "First Last""
 * also type "git config --global user.email "email@hstat.org""

---
## Repository Setup
1. go inside the workspace you made
2. type `mkdir first-repo`
   * this makes your first folder
3. type `cd first-repo` 
   * to get inside that folder
4. type `pwd`   
  * you should see this _/home/nitrous/github-learning/first-repo_
  * this also checks where you are.
5. `git init`
  * start git in our repository (repo) that was our directory for version control (do this only one time)
6. `touch README.md`
  * makes a new file 
7. open the README 
  * type anything on it
8. save 
 * if theres a little circle next to the README.md on top press it and save it.
9. then type `git add Readme.md` 
  * to add it.
10.  then type `git commit -m “write here a short message that says what you just did or change”`
11.  then type `git push`
##### Everytime you make a change repeat steps 8 to 11.
### Go back to github.com that is our remote
12. after you had already make an account
13. go to the top right coner click on the "+" and press New repository
14. give a  Repository name: ""
  * the names need to **ALWAYS** match to the name of the folder.
15. then press _create repository_
16. your going get a page like this 
 * image
  * it has to be "ssh" so it could work
17. after coping, paste line by line on the c9 but first make sure your in the folder where you did the changes
18. then go back to github.com and refresh the page and you see the changes.

---
## Workflow & Commands

git init :
is a code that is being use only one time to start git in our repository (repo) that was our directory for version control


git status : 
is a command that helps you see what was been edited since the last commit and also that give you advice on what to do if your stuck. It will show up on color red.
 

git add file.ext :
is an adding code that add the files to be committed to the stage.


git status :
the command to see the commitment file on stage. It will show green is you done the command before. 



commit 

push
