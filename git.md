*Staging*
1. git init ---to start the tracking of changes, run this in project directory.
2. git clone https_link_of_repository_on_github ---it will clone whole project into the local machine.
3. git status ---to check the latest changes in the directory.
4. git add -A ---to set/stage the changes for commit in whole repo.
5. git add . ---it will stage only inside current directory.
6. git reset ---to unset or reset the changes from stage.
7. git add * ---only stages new/modified files but not deleted ones.
8. git reset --hard ---it brings back deleted files as well with changes.
9. git reset --cached  ---only removes files from staging state.

*Authentication* (account identity) 
1. git config --global user.email "myemail.com"
2. git config --global user.name "vishal"
# global applies for every project, local will be for current repo only.

*Commit*
1. git commit -m "description"  ---to commit the changes on local machine i.e. git
2. git reset HEAD~ ---to get changes back to unstage means working area.
3. git log --full commit history 
4. git log --online ---to display commits in list format with commit id
5. git checkout (commit_id) ---changes will go to that stage of commit.
6. git diff commmit_id1 commit_id2 ---to compare 2 commits

 
*Branching*
#main branch(previuosly master)
1. git branch ---list out all branches.
2. git branch branch_name ---to create a branch(it will copy main branch)
3. git checkout branch_name ---to switch to other branch
4. git merge main -m  "comment" ---to merge main branch with current branch
5. 
 
 *Push*
 1. git push origin main ---to push the changes to github from local.
 2. 

 *fetch*
 1. git fetch ---to fetch the changes from remote/github to local git not working area.
 2. git merge ---to fetch in the working area.
 3. git pull  ---performs both fetch and merge.
 4. 

 *restore*
 1. git restore dirname/filename ---to restore uncommited changes 
 2. git stash  ---to switch to another branch without commiting curent brach changes.
 3. git stash pop ---to get the changes back after returning to the working branch.
 4. git stash apply ---to store the changes into the list event after restore them.
 
 5. 


