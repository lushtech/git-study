# Git flow




## <a href="#example_to_setup_a_git_flow">Example to setup a git flow </a>







### <a name="example_to_setup_a_git_flow">Example to setup a git flow </a> 

* 1.Create a registory in github

* 2.git clone the registory in your host and tag it 

Clone
```
git clone git@github.com:lushtech/git-study.git

cd git-study

```
You will find you are on master branch which is the default.


Tag
```
git tag v0.1

git push master v0.1

```





* 3.Bulid a new branch develop and feature/git-flow 


branch develop

```
#Build branch

git checkout -b develop


#Push local branch to remote branch

git push --set-upstream origin develop

#List the branch name
git branch -v

#To Query branch information
#for example: if master is the direct origin branch of develop branch,
#it will show the name of master branch.
git branch --merge

```


