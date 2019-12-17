# Revisions and the Cloud

## Version Control
1. **Local Version Control** - one database on your hard disk that stores changes to files
2. **Centralized Version Control (CVCS)** - This system entails a single server storing all changes and file versions, which can be accessed by various clients.  Draw back: CVS goes down, collaborators cannot work with each other on a file or save changes and new versions
3. **Distributed Version Control** - allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

--- 

## Setting up a git repository (DVC)
 Setup the directory you want to use as your repository location on your local machine. 

 - you will want to be in the current directory that you will want the repository to be located.

### CLONING!
 From your GitHub Repository, click on the __Clone or Download__ button, copy the link.

 On your command line, in your current directory enter in: 

 `$ git clone https://weblocation.com`

#### Your Repository is now setup on your Local machine!

---

## git commands

`$ git status`

finds the current status of your project between the local/cloud version.

`$ code .`

will take you to the IDE code of that current repository

`$ git add .`

this will add the changes from the IDE, will still need to be committed.

`$ git fetch`

looks to see if changes between the local/cloud repository

`$ git push origin master`

sends back to the GitHub repository

`$ git commit`

adds new commit from the IDE modifications.  make sure to add in the detailed message about the commit change.

`$ git commit -m "message about change here"`

---

# !REMEMBER!  A-C-P - Add/Commit/Push

It is best practice to remember any time that you add to your project, Commit the information and then Push it back to your Repository.



 
[HOME](https://cassandraortiz.github.io/learning-journal/)




