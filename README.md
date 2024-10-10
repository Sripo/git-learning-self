# git-learning-self
Trying to learn git

## While On-boarding (Basic steps to Clone & Build the Project)
**Step 1** : Create a `Workspace` folder in your local.
**Step 2** : Create another file with the version or basic on release then --> Right click + GitBash here
**Step 3** : Give the `git clone <git/bitbucket_ MasterBranch_URL>` command.
**Step 4** : It will clone the repository into local folder.
**Step 5** : Go to your respective IDE --> File --> Open Folder.

### Commands
-`git clone <branch_name>` : To clone the branches to your local.
- After Cloning the repository to Local either your Lead or someone will tell you where to build & install your Maven.
   -**First way (Using GitBash)**
     - Goto respective folder --> Right click --> GitBash Here.
     - Give command `mvn clean install`. By giving this command it will internally build the project.
   -**Second Way (Using Intellij IDE)**
     - If you use Intellij then on Rightside top corner there will be a `maven m` icon.
     - Click on `maven`, it will show all the commands.
- If your sprint is completed and working on new Release then
    -**First Way (Using GitBash)**
        - Goto respective folder -->Right click --> GitBash Here.
        - Give command `git checkout -b <branch_name>` that your lead or manager sent in the email.
    -**Second Way (Using Intellij IDE)**
        - Goto Intellij IDE on rightbottom --> there will be an icon of branch.
        - Click on the branch icon --> in Search bar --> search for the `<branch_name>`.
        - Once you search for that branch, it will ask you whether you need to checkout or not --> Click on `checkout`. 


## Git Commands to Push and Deploy 
Before doing anything you need to check wheather your local code is update to Parent/ master branch. For that you need to use `git pull`.
- `git pull` : Sinks your's local to Parent/Master branch.
- `git status` : To know the changes in the files which we have done.
- `git checkout -b <branch_name>` : To create the new branch 
    - if -b --> create new brach (if you don't have that branch `git checkout -b <branch_name>` will create and points local to that branch.
    - if branch already exists and if we use `-b <branch_name>` it will mention/ sends the message saying that branch exists.
    - if only checkout <branchName> --> points to that branch.
    - if you just gave the `git checkout  <branch_name>` and branch doesn't exists, sends a message stating that branch doesn't exists. 
-`git add <file_name>` : To stage the modifications in that particular file.
-`git add --a` : used to stage all the modifications in that repo (i.e., modifications in all the files of that repository)
-`git commit -m <message>` : To push the changes that we staged to Parent/ Master branch (i.e., in real-time projects we mostly get the JIRA ticket number to identify).


