1)The --global option applies a Git setting to all repositories for my user account. Without --global, the setting applies only to the current repository.



2)The ls -a command displays hidden files and folders, whose names usually begin with a dot. The .git folder stores repository information, including Git's history and configuration.


3)There were five untracked items: .gitignore, README.md, lab3 (1).ipynb, notes.md.txt.save, and week02]/.


4).DS_Store disappeared from the untracked list because it matches the ignore rule in .gitignore. Git therefore ignores this matching file when it is untracked.


5)The .gitignore file should be committed to the repository. This allows collaborators to use the same rules for ignoring unnecessary files.


6)The README.md file moves from the untracked files list into the staging area. The staging area contains changes prepared for the next commit.


7)Git displayed a summary of the commit, including the number of files changed and created. The commit message was Lab work so far.


8)The first seven characters form a short version of the commit hash. They can be used to identify and refer to a particular commit without typing the full hash.