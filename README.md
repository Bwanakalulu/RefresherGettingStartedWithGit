# What it says, just a simple GitHub refresher Exercise

## BASIC COMMANDS
git --version             // Checks if Git is installed and shows Version Nr.

git command -help         //see all the available options for the specific command

git help -all             //see all commands. If you're'stuck, SHIFT + G to jump the end ,  q to exit

$ git config --global init.defaultBranch // show default main branch

$ git config --global init.defaultBranch main // create new default main branch called main


# Create Files 

touch .ignore             // Creates a Git ignore file 

touch app.js              // Creates a fle app.js

## Configure User and E-mail
git config --global user.name "username" // Configure Git

git config --global user.email "12345@gmail.com" // Configure Git
## Get started and Initialize Your repo
git init                  // Initialize a local Git Repo

git status                // Check status of working tree will display diffs between working tree and staging area

ls                        // List files
## Add files to your Repo
git add <file>            // Add file(s) to index (to the staging area)

git add -A                // Using --all will stage all changes (new, modified, and deleted) files.  

git add .                 // ads everything to the staging area

git add *.html            // will add all html files to the staging area 
## Commit  files to your Repo
git commit                // Commit changes to index (Puts everything in to the local repo)

git commit -m 'message'   // Commits with message includedgit commit -m

git commit -a -m 'msg'    // Add and Commit changes directly

git commit -am 'msg'      // Add and Commit changes directly shorthand

## Branches
git branch Hello-World    // Creates a new branch called "Hello-World

git branch                // Shows the branches

git checkout Hello-World  // checkout is used to check out a branch. from the curr. branch, to Hello-World

git checkout -b urgent    // Using the -b option on checkout will create a new branch, and move to it

git checkout master       // Switched to branch 'master'

git merge urgent          // Now we merge the current branch (master) with emergency-fix:

git branch -d urgent      // we can delete emergency-fix, as it is no longer needed:

# WORKING WITH GITHUB
git remote add origin URL // Add Folder origin to GITHUB 

git fetch origin          // Get all the change history of the origin for this branch:

git fetch origin          // So, on your local Git, fetch updates to see what has changed on GitHub:

git push --set-upstream origin master // push everything to GITHUB

git push                  // Push to rem Repo (credentials or SSH keys required)

git merge origin/master   // We can merge our current branch (master) with origin/master:

git merge origin/master   // Merge the current branch with the branch master, on origin:

git pull                  // Pull latest from rem Repo to the current Branch

git pull origin           // Use pull to update our local Git:

git clone                 // Clones a rem Repo to your machine


git rm --cached <file>    // Unstage or delete from staging area
git log                   // To view the history of commits for a repository, you can use the log command:
clear                     // Clears the screen 
