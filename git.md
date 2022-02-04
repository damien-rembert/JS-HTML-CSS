# git


# look up meaning of:
origin
master/main
-u flag
fetch

# commands

## git status
Check the status of the repo, compares local and remote

## git pull
get, "pull", the latest version from the remote repo

## git clone
Copies, "clone", a remote repo
Shallow clone for big repo, not cloning the whole history
git clone --depth 1 <url>

## git fetch
???

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
