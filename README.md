# learnable-version-control
# learnable-week-2-task

version control is a framework that tracks changes to files, enabling people and groups to productively manage and collaborate on projects. It records each change made to a document or set of records after some time.



#THE DIFFRENCE BETWEEN GIT AND GITHUB;

Git Git is a distributed version control system used to track changes in files and coordinate work among developers. 
#Purpose: Manages source code and enables version control locally and collaboratively.
#Key Features: 
#Distributed: Every user has a complete copy of the repository.
#Works offline: Changes can be committed locally without needing an internet connection.
#Command-line-based: Typically used through terminal commands.

#Example Tasks:
 . Create repositories (git init).
 . Track changes (git add, git commit).
 . Branching and merging (git branch, git merge).
 . Push and pull changes (git push, git pull).

GitHub is a web-based platform for hosting Git repositories, providing collaboration tools and features.

#Purpose: Offers a central hub for teams to share, review, and manage code online.

Key Features:
 . Cloud-based hosting for Git repositories.
 . Collaboration tools like pull requests, code reviews, and issue tracking.
 . Integrated CI/CD, project management, and version control GUI.
 . Social features like user profiles, repositories, and following others.

 #Example Tasks:
 . Host and share repositories.
 . Review code changes with pull requests.
 . Track project issues and tasks.
 . Collaborate in real-time with team members.



#DIFFRENCE BETWEEN "GIT FETCH" AND "GI PULL":

The commands "git fetch" and "git pull" are used to update your local repository with changes from a remote repository, but they work differently as listed below;

Git Fetch
#Purpose: Downloads changes from the remote repository but does not apply them to your local branch.

#How It Works: Updates the remote tracking branches (e.g., origin/main) in your local repository.

#Leaves your working directory unchanged.
 . Allows you to review the changes before deciding to merge or rebase.

#Use Case: When you want to see what changes have been made in the remote repository without affecting your current branch.
 #Command Example:
 . bash
 . Copy code
 . git fetch origin
 . git diff main origin/main # Compare your branch with the fetched updates

 * Git Pull
#Purpose:
 Fetches changes from the remote repository and immediately merges them into your current branch.

 #How It Works: Combines git fetch and git merge in one step. Directly applies changes to your current working branch, potentially causing conflicts.

  Use Case: When you’re ready to sync your branch with the latest changes from the remote repository.
 #Command Example:
  . bash
  . Copy code
  . git pull origin main
  . Key Differences
  . Aspect git fetch git pull
  . Merges changes into the current branch.

  . No risk of conflicts.
  . Can result in merge conflicts.
  . Flexibility.
  . Allows you to review changes first.
  . Immediate changes applied to your branch.
  . Use Case To review changes before merging.
  . To update your branch with remote changes directly. 