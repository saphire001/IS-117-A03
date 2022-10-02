# Part 1 

## Git

1. Go to: https://git-scm.com/downloads
2. Download the system and version that's right for you
3. Follow the instructions for installation 

## GitHub

1. Go to https://github.com/join
2. Create your Username 
3. Add your email and password 
4. Verify your account 
5. Click  Create Account 
6. Click on create a new repository
7. Make it public and add read.me 
8. Click Create 

## WebStorm

1. Go to https://www.jetbrains.com/community/education/#students
2. Apply for licence 
3. Once Licence is approved, click WebStorm under free products 
4. Download and Install 

# Part 2

## Glossary

* **Branch**: Pointers to a specific commit. It moves along with new commits made. They are isolated lines. 
Allow for work to be done in parallel. The main line is called Master.
You can create a branch by using the git branch command. It creates a new pointer at the current commit.
To delete an existing branch you can use the git branch -d or -D command.
* **Clone**: Copy of a Repository on the computer instead of a website. Also known as making a copy. Can edit 
files on editor and use git to keep track.  Still connected to remote so changes can be pushed when online.
THis means that you can still be syned with the branch despite going offline when making changes.
* **Commit**: Saves all currently staged changes of the project. Used to see the current state of the project. 
These “snapshots” are the safe versions of the project. The snapshots are first saved locally then stored. 
This allows for features to be committed together in groups. Then sent to the central repository. This allows 
for work to be done in an isolated manner.
* **Fetch**: Allows you to add changes from remote to local. Unlike Pull, it does not commit them. It allows
you to get and review the changes before committing then into your local. 
* **GIT**: Open source program created to tracking changes in text files or code. GitHub is built on top of this. 
It was created by the author of the Linux OS.
* **GitHub**: A cloud based service website. Helps developers manage and store their code. It also helps track and 
change them and allow group work.  Uses Git and Version Control. 
* **Merge**: Used to combine two branches together, usually an independent line to the main one. 
Finds the common case and commits it. The base commit creates a new commit that merges the changes 
of each merge commit. Git automatically combines separate histories when merge commits are made.
* **Merge Conflict**: A difference that occurs between merged branches. The issue is that there are different changes 
to the same line of code in a file. It can also occur if one person deletes a file that another was working on. The 
conflict must be resolved before the merge can be completed.
* **Push**: Sends committed changes to remote. This command allows the code in local to go to remote so that others 
can see the changes made. 
* **Pull**: Fetching changes and then merging them. Changes other people made to the remote branch are added to 
your local one. Helps keep the code up to date.
* **Remote**: A version of a repository or branch that is hosted on the site. Connected to local clones for
syncing purposes. 
* **Repository**: Contain a collection of files of different versions of a project. Users use version control 
systems to create, modify and update these versions. Cloning is used to get a repo onto a local. They can also 
create and delete repositories. There are two types of repositories, bare and non-bare. Bare repositories are 
used by multi developers to share. Users are not allowed to modify or create new versions based on the mods. 
Non-bare repositories allow developers to create new modifications and versions. Cloning repositories automatically 
create these types. There are four stages a file has in a repository, untracked, tracked, staged and modified. 
Untracked files are the ones that the file was never committed nor staged. Tracked files are the ones that are 
committed but not staged. Staged files are the ones that were added and are waiting to be committed. Modified files 
are files that changed but not staged. To synchronize your main and remote repositories you need to use the git push 
and pull commands. Git pull to go from the main to remote and push for vise versa.