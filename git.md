# git


# look up meaning of:
-u flag
fetch

# commands

## git status
Check the status of the repo, compares local and remote

## git pull
get, "pull", the latest version from the remote repo

## git clone [url]
Copies, "clone", a remote repo
Shallow clone for big repo, not cloning the whole history
git clone --depth 1 <url>

## git stash

## git fetch
???

## git branch
indicates the current branch
list the branches and hightlights the current

## git branch -a 
this will show all the branches that are apart of this
repository, the -a is a flag to show all

## git branch newbranchname
create new branch named newbranchname

## git checkout [branch name]
let us change to the different branches


# glossary
## origin
"origin" is a shorthand name for the remote repository that a project was originally cloned from. More precisely, it is used instead of that original repository's URL - and thereby makes referencing much easier.
Note that origin is by no means a "magical" name, but just a standard convention.

## remote
A `remote` in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server.
In contrast to a **local** repository, a remote typically does not provide a file tree of the project's current state. Instead, it only consists of the .git versioning data.


# Initial process
## git init
Turn current folder into a git repo
## git add .
Tell git to "monitor" all the files
## git commit -m 'first commit'
Save, "commit", files to the default(?)/current(?)/local(?) repo
## git remote add origin <url>
Add a remote repo, (marking it as a copy?)
## git push -u origin master
send, "push", the current local version to the remote repo

# Creating a branch to work on a new function
# Commiting from a branch to main

``` bash
cd "/mnt/data/CN/week_4"
git init # Turn current folder into a git repo
git add . # Tell git to "monitor" all the files
git commit -m 'first commit' # Save, "commit", files to the default(?)/current(?)/local(?) repo with a message/comment
git remote add origin git@github.com:damien-rembert/CN-w4.git # Add a remote repo, (marking it as a copy?)
git push -u origin master #send, "push", the current local version to the remote repo
# OR (in case of problems?):
git push -u origin --all # pushes up the repo and its refs for the first time
git push -u origin --tags # pushes up any tags
```



