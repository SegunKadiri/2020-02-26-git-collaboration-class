# 2020-02-26-git-collaboration-class
Git training for collaboration

- `clone` : "downloading" a repository from a remote to a computer
  - You only need to do this once. Just like the `init` command
- `branch <name>`: create a branch called <name>
  - `checkout <name>` or `switch <name>`: to move `HEAD` (i.e., switch) to that branch
  - This is a test on commit on a different branch
  - `push <branch>` `pull <branch>`: we need to be more mindful which branch we want to push/pull and not automatically to master
  - This is an assignment to add a new branch
  - `checkout -b <name>`: this will create and checkout the branch in one command
- Pull request (aka merge request): this is how you merge branches on the web interface(e.g GitHub, BitBucket
  - This is also where you choose which branch you are going to merge into (default master)
  - In here there is a conversation and "files change" tab, this is where you do code review
  - When you're ready , click the green "merge pull request" button
  - don't forget to delete your branch

Update our local computer 

- Make sure you are on the master branch
- update your system with `git pull origin master`
- `git fetch --prune --all`: to clean up all your refereences on all your remotes
- `branch -d <branch>`: will delete a branch
