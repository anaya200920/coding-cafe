1)The --global option applies a Git setting to all repositories for my user account. Without --global, the setting applies only to the current repository.



2)The ls -a command displays hidden files and folders, whose names usually begin with a dot. The .git folder stores repository information, including Git's history and configuration.


3)There were five untracked items: .gitignore, README.md, lab3 (1).ipynb, notes.md.txt.save, and week02]/.


4).DS_Store disappeared from the untracked list because it matches the ignore rule in .gitignore. Git therefore ignores this matching file when it is untracked.


5)The .gitignore file should be committed to the repository. This allows collaborators to use the same rules for ignoring unnecessary files.


6)The README.md file moves from the untracked files list into the staging area. The staging area contains changes prepared for the next commit.


7)Git displayed a summary of the commit, including the number of files changed and created. The commit message was Lab work so far.


8)The first seven characters form a short version of the commit hash. They can be used to identify and refer to a particular commit without typing the full hash.

9)The four steps are edit, stage, commit, and check. I edit the files, stage changes with git add, save a checkpoint with git commit, and inspect the repository using git status or git log.


10)GitHub automatically displays a file named README.md from the repository's main directory on the repository front page. It helps visitors understand the project's purpose and contents.



11)The gh auth login command authenticates GitHub CLI with the GitHub account. 



12)After pushing,  the repository page on GitHub gets refreshed to see the uploaded files and the rendered README. This confirms that the local work has been uploaded online.



13)No, git push uploads local commits to the remote repository. It does not create or modify the commits in my local history.



14)A private repository exists on GitHub but is visible only to its owner and authorized collaborators. If no online repository exists, the project has not been created on GitHub and cannot be accessed there.