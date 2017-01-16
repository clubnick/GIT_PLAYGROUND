# GIT_PLAYGROUND

## GIT Submodules - with git engine
Based on: https://git-scm.com/book/cs/v1/N%C3%A1stroje-syst%C3%A9mu-Git-Submoduly

### add submodule  - submodule name "knowledge"
(submodules are linked in main project)
 
**cd \dev\GitHub\clubnick**
 
**git clone http://github.com/clubnick/GIT_PLAYGROUND**
 
**git submodule add git://github.com/clubnick/knowledge.git knowledge**
 
(add another github project as submodule)
 
(created .gitmodules in main folder)
 
**git commit -m 'first commit with submodule knowledge**
 
**git push --progress "origin" master:master**
 
(push main project + submodule to remote repository)
 

### clone main project with submodule/s
 
1.
**git clone http://github.com/clubnick/GIT_PLAYGROUND**
 
(submodule folder is cloned as empty)
  
to checkout also the submodules:
 
**git submodule init**
 
(submodule path is registered)
  
**git submodule update**
 
(submodule is checked-out)
 
 2.
 **git clone --recursive http://github.com/clubnick/GIT_PLAYGROUND**
  
  
### remove submodule/s from main project
  
**git submodule deinit -f knowledge**
  
(Cleared directory 'knowledge')

**manually delete folder knowledge (local) and file .gitmodules**

**commit and push to github**

(submodule deleted)
 
 
## GIT Submodules - with tortoise engine
 
 **On the main project submodule add**
 
 **fill appropriate directory - no branch - will automatically master used**
  
 **rest in** \*submodules with tortoisegit.docx\*
