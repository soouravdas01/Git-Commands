![](https://www.split.io/wp-content/uploads/Blog-2160x1080_GitandGitHubatWork-1-1920x960.jpg)

# GIT-GITHUB COMMANDS

## GIT 

### Refference video : [Watch the Video](https://youtu.be/uj4fy4kpaOA?si=hDjb67yMuFDq1BYO)

### Commands :

**1st Part :**

* 
  * pwd (mac)
  * **echo%cd% (windows)**
   
* 
  * cd Desktop/... (mac)
  * **cd Desktop\... (windows)**
 
* get init  -------*blank repo*
* pwd
* git clone ***link*** -------*clone of a existing repo*
* ls
* pwd
* cd
* ls
* git status
* **code_changes**
* git status
* git diff ***file_name***
* git status
* git add---------*staging*
* git commit -m "Commit_Message_1"
* git log
* git log -5 --------*last 5 commits*
* git show ***commit id***

**2nd Part :**

* git branch
* git checkout -b NewBranch
* git branch 
* git checkout master --------*master or main & checkout master means getting into master by checking out of the current one*
* git branch -d NewBranch --------*we must come out of that branch before deleting in this case it is NewBranch*

**3rd Part :**

* git branch
* git branch new
* git checkout new
* git log
* **change_code**
* git status
* git diff
* git add
* git status
* git commit -m "Commit_Message_2"
* git log
* git branch --------*we are in new branch and new is ahead of master*
* git mearge new --------*no update in new as new is equal to new*
* git mearge master --------*no update in new as new is ahead of master*
* git checkout master
* git merge new --------*updated in master as master was behind the new*
* git log

**4th Part :**

* git branch
* git checkout new
* git log -3
* git reset --hard Head^ --------*remove commit and code*
* git log -3
* git reset --soft ***previous commit id*** --------*remove commit only and code present in stage state*
* git status

**Note :**

* local mater ----> **master**
* remote master ----> **origin master**

**5th Part :**

* cd Desktop/...
* git branch
* git status
* git restore --stage ***file_name***
* git restore ***file_name*** --------*new branch is restored not master*
* git status
* git checkout master
* git log
* git pull --------*pull is used to fetch changes from remote repository & in this case no update as no changes is made in origin master from the time of copy*
* git log -3
* git push
* **provide_id** --------*origin master is updated as master branch had two commits*

**6th Part :**

* git branch
* git log -3
* **code_changes**
* git status
* git diff
* git status
* git add ***file_name***
* git status
* git commit --amend --------*when we want to make changes with same commit id and don't want another commit id then we use this*
* **press Esc then wq then enter**



                                  -----------------------------xxxxxxxxxxxxxxxxxxxxxxxx-------------------------------

  

## GITHUB

### Refference video : [Watch the Video](https://youtu.be/fMdfDnGX9S8?si=B9RpDfPFDUfYSA45)

### Commands :



