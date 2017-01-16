# GIT_PLAYGROUND

## GIT Submodules 
Based on: https://git-scm.com/book/cs/v1/N%C3%A1stroje-syst%C3%A9mu-Git-Submoduly

### Submodule knowledge
 (submodules are linked in main project)
 
 **cd \dev\GitHub\clubnick**
 
 **git clone http://github.com/clubnick/GIT_PLAYGROUND**
 
 **git submodule add git://github.com/clubnick/knowledge.git knowledge**
 
 (add another github project as submodule)
 
 (created .gitmodules in main folder)
 
 **git commit -m 'first commit with submodule knowledge**
 
 **git push --progress "origin" master:master**
 
 (push main project + submodule to remote repository)
