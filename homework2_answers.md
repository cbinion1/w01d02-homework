Part 1:

//1. One would use the git init command to set up a repository on a local computer.
//2. One would use the git add command to start tracking a file on the local repsoitory.
//3. One would use the git commit command to move the file from the staging area into the repository.

Part 2:

//1. One would use the git pull command which acts as both a fetch and merge command when pulling from master repo
//2. One would use the git reset [file name] command to unstage a file.
//3. One could us the git reset [commit] to move back to a previous commit.
//4. It's important to use -- when moving back to a previous commit so that a previous commit is selected and all history and changes are preserved both on the local and the remote repos.
//5. One might want to reset back to a previous commit due to making errors and accidentally committing them to the master.

Part 3:

//1. One would use the git branch [branch name] command to create a branch.
//2. One would use the git checkout [branch name] command to switch to a different branch.
//3. One would want to use a branch as opposed to the master in situations where one is creating and testing code and doesn't want to create possible code conflicts within the master.  A branch would be used for testing purposes.