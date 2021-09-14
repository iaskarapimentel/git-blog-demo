*# Simple Git Demo

* Create your local Git repository.
* `mkdir simple-git-demo`
* Go into your project folder and add a local Git repository to the project.
* `cd simple-git-demo`
* `git init`
* Let's add some content.
* `nano README.md`
* `"The content is alreary here"`
* `control X` `Y`
* **Staging** 
*  Any file which is not added to the staging area will not be committed. This gives the developer control over which files need to be committed.
* `git add READM.md`
* **Commiting**
* Commiting is the process in which the code is added to the **local repository**.
* `git commit -m "README added"`
* Now modify the README.md file and add the following snippet:
* ```Status
Use `git status` to find out information regarding what files are modified and what files are there in the staging area.
* `git status`
* `git add .`
* `git commit m- "more information"`
* ### BRANCHES
* A branch in nothing but a pointer to the latest commit in the Git repo. 
* `git branch test`
* `git checkout test`
* The following command will list all in local the branches.
* `git branch`
 

 


  











