# My First Repo

## Terminal Steps for Creating a Repo

1. Open the terminal and make sure it is in the correct directory.
2. Initialize repo, tell gitbash to track. Creates repo ONLY on local.
    - Terminal command: `git init` <- git initialize.
3. Create the online repo to connect with. Go to github.com and click create `new repo`
4. Give it a name and hit `create repository`
5. Copy `git remote add origin` command and paste in vsc terminal and hit enter.
    - This command links your local repo to the remote destination
    - Check this by running the command `git remote -v` shows a remote destination if you have one.

    ## Steps to make and commit a new version of your project
1. `git add .` - add all files in this directory to a new project version ** This does not commit, it just stages them**

    ## Vocab:
    - `commit` - to save a version, you can commit locally, push commit to git hub.