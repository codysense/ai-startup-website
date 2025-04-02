# Git Basic Mini Project 2
<p> This is a mini project to practice Git commands. </p>
<p> The project is aimed to help you understand the basic commands of Git. </p>

## Task 1: Create a new repository
1. Created a new repository on github and then cloned it to your local machine.
![](./img/repo_img_1.png)

2. Cloning the repository.
![](./img/repo-cloning_2.png)

3. Created folder for the repo using `mkdir` command.
![](./img/created-folder-for-the%20project_4.png)



4. Moved to the cloned directory using `cd` command.

![](./img/moved-into-the-repo_6.png)

5. Created a new file using `touch` command.
```git touch <file-name>```
    <p> This command will create a new file in the current directory. </p>
![](./img/created-index.html_7.png)

6. Checked the status of the repository using `git status` command.
```git status```
    <p> This command will show you the current status of the repository. </p>
![](./img/checked-if-changes-staged_8.png)

7. Added the file to the staging area using `git add` command.
```git add <file-name>```
    <p> This command will add the file to the staging area. </p>
![](./img/staged-index.html_9.png)

8. Committed the changes using `git commit` command.
```git commit -m "<commit-message>"```
    <p> This command will commit the changes to the repository. </p>
![](./img/commit-and-push-to-main_10.png)


9. Check current branch using `git branch` command.
```git branch```
    <p> This command will show you the current branch. </p>
![](img/check-current-branch_12.png)

10. Created a new branch for Tom using `git checkout -b` command.
```git checkout -b <branch-name>```
    <p> This command will create a new branch and switch to it. </p>
![](img/created-and-switched-to-update-nav-branch_13.png)

11. Confirmed the branch using `git branch` command.
```git branch```
    <p> This command will show you the current branch. </p>
![](img/check-branch-switch_14.png)

12. Editing the html file on Tom's branch.
```git touch <file-name>```
    <p> This command will create a new file in the current directory. </p>
![](img/Tom-nav_15.png)

13. Confirmed the changes using `git status` command.
```git status```
    <p> This command will show you the current status of the repository. </p>
![](img/checking-changes-in-tom_16.png)

14. Added the changes to the staging area using `git add` command.
```git add <file-name>```
    <p> This command will add the file to the staging area. </p>
![](img/staging_&_confirming_tom_17.png)

15. Commit and push the changes to the remote repository using `git commit` and `git push` commands.
```git commit -m "<commit-message>"```
```git push origin <branch-name>```
    <p> This command will commit the changes to the repository. </p>
    <p> This command will push the changes to the remote repository. </p>
![](img/commit-and-push-TomBranch_18.png)

16. Switched back to the main branch using `git checkout` command and pull changes to get updated after Tom Branch push.
![](img/switched-back-to-main-and-pull-changes_20.png)



17. Checkout and switched to add-contact-info branch using `git checkout` command.
```git checkout <branch-name>```
    <p> This command will switch to the specified branch. </p>
![](img/checkout-and-switched-to-contact-info_21.png)

18. Adding contact information to index.html using nano commands
![](img/contact%20information%20added_22.png)

19. Staged and Commit contact info using 'git add file-name' and 'git commit -m 'message''

![](img/staged-and-commit-contact-info_23.png)

20. Push Jerry branch using 'git push origin'
![](img/pushed-contact-info_24.png)


