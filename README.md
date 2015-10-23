## A Git Story
So how does git work in the real world

### The Idea
Git is a beautiful concept and sometimes a general workflow cheatsheet is needed to reference best practices.

### Things to note
This document uses square brackets, [ ], to represent some information that the user
is required to enter. The document will do its best to explain where the required information
can be found.

### The Flow
0. Setting up your git environment variables
1. Cloning the Master Repository
2. From Master to Develop
3. Pulling Changes from Develop
4. Creating your own branch
5. Modifying and Editing your Files
5. Staging your files for commit
6. Commiting your files
7. Pushing your branch upstream
8. Asking for a pull request
9. Peer review

#### Cloning the Master Repository
You got an awesome new job at a company that heavily uses GIT! You are a kick ass developer who used another repository at your old company. Your first task is to get the project onto your computer.

*Cloning a repository*
```
git clone [git url]
```

#### From Master to Develop
When we create our first project we create a repository called master by default. In the real world we like to create what we call a branch. A branch is a separate self contained box we can work in without effecting other peoples work spaces.

A develop branch separates our live codebase from our work in progress codebase.

*Checking out the develop branch of our project*
```
git status
git checkout develop
git status
```

#### Pulling Changes from Develop
A bunch of our collegues have been working hard on implementing a set of really cool features, so how do we get all these changes they have done? We use gits most awesome feature. We can pull from any branch that we have checked out.
```
git pull
```

#### Creating your own branch
```
git checkout develop
git pull
git branch enhancement/add_background_image
git checkout enhancement/add_background_image
```

#### Modifying and Editing your Files
```
git status
```

#### Staging your files for commit
```
git add .
```

#### Commiting your files
```
git commit -m "Added my really cool background image"
```

#### Seeing your commits
```
git log
```

##### Adv. When to use --fixup
```
git log
git commit --fixup [commit id]
```

##### Adv. When to use --squash

#### Pushing your branch upstream
```
git push
```

#### Asking for a pull request on Github

#### Peer review
