# git vs github notes

## >Version Control
*Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.*

## >Local Version Control
*Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.*

## >Centralized Version Control
*The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS).*

## >Graphical Clients
*Git includes inherent Graphical User Interface (GUI) tools. However, users can also utilize third-party tools created for particular platforms.*

## >GUI Clients
*You can access a variety of GUI clients for Mac, Windows, and Linux via the following link:* 
[https://git-scm.com/downloads/guis](click here)

## >Configuration of Variables
*An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.*

## >Check Settings
*To check settings, use the git config --list command.*

## <Tracking and Staging a New File
*Single File*

## <Track one file only by using the following format:
*git add filename*
*All Files*
*Track all files in a repository by using the following command:*
*$ git add '*'*
*After using these commands, files are tracked and staged for committing.*
*After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:*
*$ git status*
*On branch master*
*Changes to be committed:*
*(use "git reset HEAD ..." to unstage)*
*new file: EXAMPLE*
*This information tells us that there are changes to be committed and that the file has been staged.*

## <Committing a File
*After staging one or multiple files, you should commit the changes and record what you did within the commit message:*
*$ git commit -m “made change x,y,z”*
*This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD.*

## <Committing All Changes
*$ git commit -a*
*This command commits a snapshot of all modifications to tracked files in the working directory.*

## <Pushing Changes
*Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general* *overview of pushing changes to remotes.*

## <Example:
*$ git push origin master*
*This command pushes changes from the local “master” branch to the remote repository named “origin”.*
*For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository.* 
*However, these names can be changed by the user.*


[Link back to Table of Contents](README.md)
