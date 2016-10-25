# GitHub Tutorial

_by David_

---
## Git vs. GitHub
#### Git
Git is used to manage code when ever its a large or small project. It also keeps various versions of your project to go back to. Having different versions of a project is helpful incase something goes wrong or if you changed something and want to go back to previous version. Git **DOES NOT** require github.
#### Github   
Github is a website that works well with git. The website allows you to save versions of your project on the cloud. Github also uses a simple interface that makes it easy to check your files, commits, and repositories. Github **REQUIRES** git.



---
## Initial Setup
In order to use git you need to make a Github account. You will need to go to[Github](https://github.com/).   
![](github-learning/github-tutorial/Git Photos/Github-create-an-account.png)   
After you have created your account, you will need to verify your account using the email you used to sign up with. After you have done all    of this go to [Cloud9](https://c9.io/) and log in using the green cat icon on the top right. After making an account you have to connect your c9 account to your github account using SSH keys. On github press the down arrow next to your profile picture and click on settings. Now on the left click on SSH and GPG keys. Open a new tab and go to your c9 account and login. After logging in you will see the word    workspaces on the left. Now click on the gear icon on the right. After that click on SSH keys on the left. Copy everything in the grey box. It starts with "sh-rsa". Now back to github. On the rightish there should be a button called "New SSH Key". Click on the button and type "cloud9" in the title and paste the SSH key on the box under the title called "key". Now your all set!


---
## Repository Setup
Make a directory using "mkdir". Also make sure your in workspace. After making a directory cd into it and type "git init" to actually use git commands.
 


---
## Workflow & Commands
* **git status** - This command is very useful. It tells you what is going on in repository and if any commands used before worked or not.
* **git push** - This allows you to push a commit to the cloud and use it later.
* **git clone "URL"** - This command allows you to copy a repository 
* **git commit -m "message"** - This git command allows you to take a snapchat and save what ever you have done.
* **git add "file"** - add a file so you can commit it.
* **rm -rf** - this allows you to delete a directory even if there are files inside of it.
* **git reset HEAD --"file"** - If you accidently staged a file, this command will unstage it.
* **git add remote origin "URL"** - this command allows you to add an external link. You will need to add a link before using git push.
* **git add .** - This command puts all files to the stage and ready to be committed.