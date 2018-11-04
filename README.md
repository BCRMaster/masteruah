# masteruah
First Repository

- git init creates a new Git repository
- git status inspects the contents of the working directory and staging area
- git add adds files from the working directory to the staging area
- git diff shows the difference between the working directory and the staging area
- git commitpermanently stores file changes from the staging area in the repository
- git log shows a list of all previous commits


MacBook-Pro-de-Beich:github Beich$ git clone https://github.com/BCRMaster/masteruah.git
Cloning into 'masteruah'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
MacBook-Pro-de-Beich:github Beich$ cd masteruah
MacBook-Pro-de-Beich:masteruah Beich$ git add .
MacBook-Pro-de-Beich:masteruah Beich$ git commit -m "commit inicial"
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
MacBook-Pro-de-Beich:masteruah Beich$ git push origin master
Everything up-to-date