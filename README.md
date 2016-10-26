# GitHub Tutorial

_by David_

---
## Git vs. GitHub
#### Git
Git is used to manage code by keeping various "snapshots" of your code to refer back to. Having different versions of a project is helpful because incase something goes wrong or if you changed something and want to go back to previous a version. Git **DOES NOT** require github.
#### Github   
Github allows users to save the different versions of your code into the cloud. Github also uses a simple interface that makes it easy to check your files, commits, and repositories. Github **REQUIRES** git.



---
## Initial Setup
In order to use git you need to make a Github account. You will need to go to [Github](https://github.com/).   
![Imgur](http://i.imgur.com/dQYkvqW.png)   
After you have created your account, you will need to verify your account using the email you used to sign up with. After you have done all of this go to [Cloud9](https://c9.io/) and log in using the green cat icon on the top right. After making an account you have to connect your c9 account to your github account using SSH keys. On github press the down arrow next to your profile picture and click on settings. Now on the left click on SSH and GPG keys.   
![Imgur](http://i.imgur.com/y0vE8Zt.png)   
Open a new tab and go to your c9 account and login. After logging in you will see the word "workspaces" on the left. Now click on the gear icon on the right.   
![Imgur](http://i.imgur.com/3U4SXPA.png)   
After that click on SSH keys on the left. Copy everything in the grey box. It starts with `ssh-rsa`. Now go back to the github tab. On the top right corner, there should be a button called "New SSH Key". Click on the button and type "cloud9" in the title and paste the SSH key on the box under the title called "key". Now your all set!


---
## Repository Setup
Make a directory using `mkdir`. Also make sure your in workspace. After making a directory cd into it and type `git init` to actually use git commands.   
![Imgur](http://i.imgur.com/V14Uphr.png)   
Now you will need to connect your repository to github in order to push commits to the cloud. First go to github. After this click on the plus sign on the top-right. Then choose "new repository". The name of the repository has to be the same as the directory you made in cloud9. For example if im working on a project called "git tutorial" in cloud9, then the name of the repository in github should also be "git tutorial". It's also case sensitive! After typing the name press the green button on the bottom to create it! Then you should see a page with the words "Quick Setup" on the left. Make sure you chose SSH or if you feel like logging in everytime you open the repo in cloud9, then feel free to choose https. Now copy both lines of code under the header "…or push an existing repository from the command line". Paste the two lines of code into the command line in cloud9 and press enter. Also make sure you are in the correct repository or it will not work. Now you can simply type "git push" to upload commits to the cloud.   
![Imgur](http://i.imgur.com/DE2YlAw.png)
---
## Workflow & Commands
* **git status** - This command tells you what is going on in the repository and if any commands used before worked or not.
* **git push** - This allows you to push a commit to the cloud and use it later.
* **git clone "URL"** - This command allows you to clone a repository into your lov
* **git commit -m "message"** - This git command allows you to take a snapchat and save what ever you have done.
* **git add "file"** - add a file so you can commit it.
* **rm -rf** - this allows you to delete a directory even if there are files inside of it.
* **git reset HEAD --"file"** - If you accidently staged a file, this command will unstage it.
* **git add remote origin "URL"** - this command allows you to add an external link. You will need to add a link before using git push.
* **git add .** - This command puts all files to the stage and ready to be committed.