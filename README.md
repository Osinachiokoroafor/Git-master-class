# Git-master-class
## EXPLAIN VERSION CONTROl

  - VERSION CONTROL:
   Version control also known as source control or revision control- is an important software development practice for tracking and managing changes made to code and other files. Version control serves as a safety net to protect the source code from irreparable harm, giving the development team the freedom to experiment without fear of causing damage or creating code conflicts.
  If developers code concurrently and create incompatible changes, version control identifies the problem areas so that team members can quickly revert changes to a previous version, compare changes, or identify who committed the problem code through the revision history. With a version control system (VCS), a software team can solve an issue before progressing further into a project.Through code reviews, software teams can analyze earlier versions to understand the changes made to the code over time.

## EXPLAIN DIFFERENCE BETWEEN GIT AND GITHUB
    
  - GIT:
   Git giis a Version Control System (VCS); A source tool that helps in tracking and managing codes. It was designed to assist programmers working in coordination and tracking changes in any of the files associated with the local directory. Unlike other version control systems, GIT is hassle-free, fast, and absolutely free of cost to use.Git has some features that has made it exceptional.(eg)
  - DISTRIBUTION: One of the fine features of GIT is that it has a distributed system. It allows multiple people to work  on a project simultaneously without interfering with each other’s work. 
  - BRANCHING: GIT allows users to work parallelly on different domains through branching. Through this, multiple users can try the same feature in various ways and then merge the one they feel is the best to the main branch. 
  - SECURE: GIT records all the commits done by the users on their local copy.
     
      while

  - GITHUB is designed as a repository hosting service. It also gives a wide range of features such as collaborating on  the   project, resolving issues, source code management, and exchanging ideas with people around the world. Along with this, it provides the features of GIT too. GITHUB  to GIT is the same as a photograph is to a person. It provides a     graphical user interface to the command line tool GIT.
   - Features of GitHub
   As mentioned before, GitHub has a wide range of features. These features include 
  - GitHub Gist: Sharing code snippets and notes instantly.
  - GitHub Flow: A workflow to track all the branch-based activities at regular intervals.
  - GitHub Pages: Users can directly deploy their static web pages that pull over the data and changes from the respective  repository.
  - GitHub Students Developer Pack: A space full of cloud resources, developer tools, and programming tools oriented towards the benefit of students.

 ## ALTENATIVES TO GITHUB
 
- GitLab - is an open-source code repository that provides free open and private repositories, issue-following capabilities   and collaborative programming improvement stages for enormous DevOps and DevSecOps projects, enabling professionals to perform all the tasks in a project. GitLab offers an area for online code stockpiling and capacities for issue tracking and CI/CD. The vault empowers facilitating diverse improvement chains and forms and helps teams reduce   product life cycles and  increase productivity, which in turn creates value for customers.
  
- Bitbucket -is version control tool developed by Atlassian. It is more than just Git code management. Bitbucket is one the best alternatives to GitHub which allows the team to plan projects, collaborate on code, test, and deploy.
 - Features:
 - Free unlimited private repositories
 - Allows you to build quality software with code review
 - Helps you to secure your workflow
 - Bitbucket lets you build, test and
 
 - SourceForge-is an open source development and distribution platform. The tool is hosted on Apache, Allura, and supports many different projects. Users can select either Git, Mercurial as their version control system.
 Features
 - Extensive worldwide mirror network
 - Integrated Issue Tracking
 - This GitHub alternative open source allows browser-based code browsing
 - You can download statistics by platform, over time, and by region.


 ## DIFFERENCE BETWEEN Git GIT FETCH AND GIT PULL

  The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while
  git fetch does not. The git fetch command only copies changes into your local Git repo  The git pull command does both.
  They are several Benefits of using the git fetch command...
  If you are actively working on files tracked by Git, but you still want to update your local repository with the latest   changes from a remote repository, use the git fetch command.
  A git fetch updates your local repo with all of the latest changes from a remote repo but doesn’t make any changes to your local workspace.
      They are also benefits of using git pull which are:
  If a developer finds out that there are new, updated files on a remote repository like GitHub, they will likely want to copy those changes from GitHub to both their local repository and into their working directory.
  This is what the git pull command does. The git pull command updates both the user’s local Git repository and the files in their working directory.
 
 ## Git REBASE AND ITS COMMANDS.

 Git Rebase is the process of moving or combining a sequence of commits to a new base commit. Rebasing is most useful and
 easily visualized in the context of a feature branching workflow.it also helps in debugging faster.  
 There are six commands available while rebasing:

- PICK:
  pick simply means that the commit is included. Rearranging the order of the pick commands changes the order of the   commits when the rebase is underway. If you choose not to include a commit, you should delete the entire line.

- REWORD:
  The reword command is similar to pick, but after you use it, the rebase process will pause and give you a chance to alter the commit message. Any changes made by the commit are not affected.

- EDIT:
 If you choose to edit a commit, you'll be given the chance to amend the commit, meaning that you can add or change the commit entirely. You can also make more commits before you continue the rebase. This allows you to split a large commit into smaller ones, or, remove erroneous changes made in a commit.

 - SQUASH :
  This command lets you combine two or more commits into a single commit. A commit is squashed into the commit above it. Git gives you the chance to write a new commit message describing both changes.

 - FIXUP :This is similar to squash, but the commit to be merged has its message discarded.The commit is simply merged into the commit above it, and the earlier commit's message is used to describe both changes.

 - EXES :
 This lets you run arbitrary shell commands against a commit.

 ## GIT CHERRY-PICK AND ITS COMMAND
  Git cherry-pick is a powerful command that allows any specific Git commits to be selected by reference and append to the current working HEAD. The act of picking a commit from a branch and adding it to another is cherry picking. For undoing modifications, git cherry-pick can be useful. Say, for example, that a commit is made to the wrong branch unintentionally. You may turn to the right branch and select the commit to where it is supposed to belong.
  - Git cherry-pick commands :
  - Git cherry-pick <hash commit>