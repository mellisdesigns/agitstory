## A Git Story
A Git Story, how we use git in the real world.

### The Idea
Git is a beautiful concept and sometimes a general workflow cheatsheet is needed to reference best practises.

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
```
git clone git_url
```

#### From Master to Develop
```
git status
git checkout develop
git status
```

#### Pulling Changes from Develop
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

#### Pushing your branch upstream
```
git push
```

#### Asking for a pull request on Github

#### Peer review