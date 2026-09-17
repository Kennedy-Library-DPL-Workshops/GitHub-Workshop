<p align="right"><a href="SettingUpGit.md">Setting Up Git -> </a></p>


# Intro to Git and GitHub Workshop  

Welcome to the Digital Project Lab's Introduction to Git and GitHub Workshop! In this repository we will cover
* how Git works
* getting started with Git
* creating and updating a GitHub repository with version control
* where to learn more!

## First things first, what is Git?
Git is a software system that makes it possible for coders to develop collaboratively by using version control. ​**Version control** is the process of tracking changes to files over time, allowing coders to revert to previous versions, collaborate, and manage code history. 

Have you ever worked simultaneously with others on a Google Doc or Microsoft Word document, only to realize that the changes you were making were overwriting or conflicting with someone else's? In contrast, Git works by giving each team member a copy (clone) of the entire project to work from on their own machine. This structure is called **Distributed Architecture.** ​

#### Distributed Architecture
<img src="/image/distr_architecture.png" alt="Diagram explaining distributed architecture" width="300"/>

## How does Git work?

### Repositories
Each coding project that uses Git is stored in a **repository,** a folder that contains all the project's files and their history of changes. This includes code files, as well as files containing information about the project, such as a README file.

Git works by allowing project team members to create copies of the project repository on their individual computers, called **local repositories.** At the same time, a global repository is maintained as the source of truth. Team members push changes to the global repository as they make updates to the project. Typically, this global repository is made available through a server or online platform like GitHub, in which case it is called a **remote repository.**

### Version control

When a coder makes code updates to their local repository, they use Git's **stage** and **commit** functions to create a snapshot of the project, documenting who made changes, when, and why. Then, the coder uses the **pull** function to reconcile their local repository with the global remote repository, checking that their code reflects any new updates made by other team members. Finally, the coder uses the **push** function to send their code updates to the global remote repository, along with the information from their commit. The coder's local repository then is in sync with the remote repository -- until someone else pushes changes to the remote repository. This process enables simultaneous work by multiple coders without mutually overwriting files. 

This process of tracking and managing changes from local repositories to a remote source of truth is called **version control.**

#### Version Control
<img src="/image/Github_Workflow.jpg" alt="Diagram explaining version control" width="300"/>

It serves as a central hub for collaboration and also a backup if anything happens to your machine​

​

README: a file w/ info about your project. Written in plain text​


[Now on to set up Git on your computer!](SettingUpGit.md)  

---

**Contributers**  
Madison Lopez | Claire Burns







