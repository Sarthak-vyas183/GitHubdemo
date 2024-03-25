GitHubdemo <br>
by sarthak vyas 
from bhopal 
to open a repository in vs code we use <br>
git clone commad which is  <br>
git clone (then past repository link https://............ <br>

statu command --- display the status of code  <br>
git status

to commit a file from vs code to github <br>
1.git add .     /// . (dot) is stand to commit all the file which is updated in vs code 
2.git.commit -m "some message"    <br>
To upload local repo content to gitHub We Use <br>
3.git push origin main 


To send a folder(repo) to the git 
1 . git init
2. git add .
3. git commit -m"some message"
4. git remote add origin <---repository link---->
5. git push origin main 

 To in another branch :  
  To go in another Branch : 
1. git checkcout <--branch name-->
2. git checkout <--new branchname-->
3. git branch -D <--branchname-->  this command use to delete the branch 

To merge two branch 
to chekc difference : 
1. git diff main
2. git merge main



your Team is collaborating to your code .  Hence project development is faster  


seven steps of Collaboration : 

1 . Fork the target repo to your own account . 
2 . Clone the repo to your local machine .
    I . git clone <--link of repo-->

3 . After colning checkout a new "topic branch" and make changes . 
         I . git checkout -b <branch name>      eg . git checkout -b login-page
         II . git branch          (this command is use to check your current working branch)

4 . Puch your Topic branch to your fork . 

5 . commiting : 
         I git add .
         2 git commit -am"msg"
         3 git push origin <branch name> eg  --- git push origin login-page  

6 . creating a Pull request : 
    go to the github account and click on button compate&pull  

7 . In the author account you go in pull request section then check and merge the code in the main branch .
