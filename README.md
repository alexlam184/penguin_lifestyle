


## Welcomr to Penguin world



---
## Precondition:
Node JS is installed in computer
create-react-app  (not used)
create-next-app


---

## Project website (open it after npm start)
  - Local:            http://localhost:3000        


### We suggest that you begin by typing:
```bat
  cd penguin_lifestyle
  npm run dev
```

## stop run npm in terminal 
```bat
Ctrl + C ,then y to stop the app

```
To know more npm command, click [here](react_guide_readme.md)




---

## Installing 
Clone & create new branch  **slave02** </br>
*!!!!! PLEASE MAKE SURE YOU CREATE NEW BRANCH IN **GITHUB** !!!!!!*

```bat

git clone https://github.com/alexlam184/penguin_lifestyle.git
git fetch 
git checkout slave02

```
## Add new folder
Add  all traced or untraced file for commit
```bat
git add .
```


## Update branch 
*!!!!! PLEASE **PULL** BEFORE **PUSH** !!!!!!* </br>
Push to branch **slave01**
```bat

git commit -m 'readme change v5'
git push origin slave01 
```

## Sync with local project with Github branch 
git pull = git fetch + git merge </br>
**fetch**: download new file(s) from Github </br>
**merge**: update your local project </br>

```bat
git pull --rebase
```
## Check branch
View current branch & other branch
```bat
git branch
```
## Update master branch with slave branch
*!!!!! PLEASE **PULL** BEFORE **PUSH** !!!!!!* </br>
Update master branch wit slave branch
```bat
git diff master slave01
git checkout master
git merge master slave01
git checkout slave01
git branch
```

## Update slave branch with master branch
Update slave branch with master branch
```bat
git checkout slave02
git pull origin master
```

## Master branch confirm update
push the update commit to master branch after merge
```bat
git checkout master
git push
```


[Github guideline in Chinese](https://gitbook.tw/chapters/github/pull-from-github.html) </br>
[Github project download guideline](https://support.atlassian.com/bitbucket-cloud/docs/clone-and-make-a-change-on-a-new-branch/)
---

## Tech Stack

**Client:** React, Next

**Server:** Node

**Backend:**

## Release


---
## Contributor
- Alex Shiu <https://github.com/sysalex0?tab=repositories>
- Alex Lam <https://github.com/alexlam184>
---

## Licence & copyright
- [MIT](https://choosealicense.com/licenses/mit/)



