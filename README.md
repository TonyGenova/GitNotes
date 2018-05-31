### GitNotes
##### Basic notes for git bash use

Create a local directory in current directory - need tilde to reference current directory
```bash
mkdir ~/RepoName
````

initialize git for current directory
```bash
git init
```

Add remote directory to local git, and clone current files on repo to local dir
```bash
git remote add origin https://github.com/UserName/RepoName.git
git clone https://github.com/UserName/RepoName.git
```

Push local files to repo
```bash
git add . #adds all current files in working dir to version control
git commit -m "Add message here" #updates local repo only with current updates
git push origin master #push local files to remote repo
```
