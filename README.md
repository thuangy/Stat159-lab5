# Stat159-lab5
User A: Tina Huang
User B: Yoon Rho

Task 1:

User A made the repository and User B cloned this repository, both users could make new files, modify them, and add them to the same directory, as long as each user pushed and pulled to the repository as soon as changes were made. 

Task 2:

There is a conflict because both users modified the same file, and user A already pushed changes to file2.txt and user B didn't pull the remote changes. Make sure users' repositories are up to date with the remote before they try to push to it. To resolve the conflict, User B has to pull from the remote and then manually go into file2.txt and select which lines they actually want to keep, and then add, commit, and push the new file. 

Task 3:

User B made a new branch and changed file1.txt, but User A also modified this file, so there was a conflict. When User B pulled from the remote, Git showed in the file the two modifications that were made and merged them into the same file, so User B had to manually select which modification to keep, and then added, committed, and pushed the file again. 

Task 4:

Both users created new branches, User A modified file1.txt while User B modified file2.txt on separate branches, User A merged to master and pushed the changes to master first so User B merged to their local master but had to pull first before pushing their changes, and they had to create a new commit to merge the remote changes made by User A into their local repository. 

Task 5:

Both users created new branches, and both users modified file1.txt in those new branches. User B merged their branch into master and pushed to the remote, so when User A tried to also push their master after merging in their branch, the push was rejected. User A had to pull from the remote first, which prompted a new commit to be created merging the changes, and then User A could push the combined changes to the remote. 
