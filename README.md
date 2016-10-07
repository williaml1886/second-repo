# second-repo
williaml1886:~/workspace (master) $ cd ~/workspace
williaml1886:~/workspace (master) $ mkdir second-repo
williaml1886:~/workspace (master) $ cd second-repo
williaml1886:~/workspace/second-repo (master) $ git init
Initialized empty Git repository in /home/ubuntu/workspace/second-repo/.git/
williaml1886:~/workspace/second-repo (master) $ touch README.md
williaml1886:~/workspace/second-repo (master) $ git add  "README file created"
fatal: pathspec 'README file created' did not match any files
williaml1886:~/workspace/second-repo (master) $ git commit -m "Add README file"
On branch master

Initial commit

Untracked files:
        README.md

nothing added to commit but untracked files present
williaml1886:~/workspace/second-repo (master) $ git commit -m "create readme"
On branch master

Initial commit

Untracked files:
        README.md

nothing added to commit but untracked files present
williaml1886:~/workspace/second-repo (master) $ git remote add origin git@github.com:williaml1886/second-repo.git
williaml1886:~/workspace/second-repo (master) $ git push -u origin master
error: src refspec master does not match any.
error: failed to push some refs to 'git@github.com:williaml1886/second-repo.git'
williaml1886:~/workspace/second-repo (master) $ git push
error: src refspec master does not match any.
error: failed to push some refs to 'git@github.com:williaml1886/second-repo.git'
williaml1886:~/workspace/second-repo (master) $ -u origin master
bash: -u: command not found
