<p align="left"><a href="ACTIVITY.md"> <- Activity </a> </p>

# Version Control with Git

---

## The Git Workflow
<img width="600" alt="Github Workflow" src="https://github.com/user-attachments/assets/55fa72c1-26a7-4a87-9ba5-0aac28b99e9e" />  

### IDE  

Most IDE's have git support, where you can stage, commit, and push/pull through the IDE in an easier interface than through the terminal.

Usually it looks something like this:

1. A "Source Control" or "Version Control" tab on the side or top of the IDE.
2. A text prompt to write a Commit message.
3. Modified files list, with an option to stage/unstage files.
4. A Graph showing the commits on the remote branch and the commits on the local brach (usually in different colors)

### Git commands for the Terminal     
[Git Command Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)  

> git status

*Show modified files not yet staged for a commit*  

> git log

*Show commit and push history*  

> git add [file] [-A]

*Add a file to your stage*  
\**-A adds all modifications made*

> git commit -m “[descriptive message]”

*Commit your staged changes with a message to your local branch*  

> git push 

*Push your commits to your remote branch*  

> git pull

*Pull all changes made in remote branch to local branch*  
