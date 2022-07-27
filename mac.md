## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?

Git is a version control system that allows for tracking of changes and versions of files. It is mainly used by 
programmers who collaborate to build software together.

2. What is the difference between Git and GitHub?

While Git is a version control system and set of commands used to track, change, add, commit, and push files/code, Github 
is a cloud-based hosting service that holds repositories of code and files and displaying information regarding the 
changes made, etc.. You can use both Git and Github in conjunction to work on a project individually or collaboratively with Git making the changes and Github storing the 
files/code.

3. Why do we create a branch?

Branches are our personal workspace copies of the code/file we are working with, as opposed to the main (or master). We 
create branches so that we have our own copy where we can add features, fix bugs, make suggested changes, etc. without 
affecting the working main code. Later, we can use pull requests where a senior developer will check and make suggestions 
before merging the branch into the main.

4. What is the purpose of a Pull Request?

After pushing our code into the branch, we can use a Pull Request to merge our branch code/files into the main code/files. 
Team members and/or Senior Developers can check the code/files on the branch before fully merging any changes into the 
main branch.
 
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.

'git check out' is the command to change branches. For example : 'git checkout main' will switch you to the main branch 
from the current one. You can use git branch to see which branches exist on your local version and which one you are 
currently in.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?

git fetch: will retrieve the latest meta-data information from the remote repository. This will not actaully download 
anything - it is just a check for recent changes.

git pull: will both check the latest changes and also bring down any changes from the remote repository to the local.

git merge: will merge any changes that were made to the code base on a seperate branch to the current as new a commit. 
You will need to commit all changes beforehand as git will not allow a merge unless all changes in the current branch have 
been committed.

7. What is a merge conflict?

A merge conlict can occur when branches that have conflicting/competing commits are merged (eg. different changes to the 
same line of code in the same file). All conflicts must be resolved before merging pull requests.

8. How do you resolve a merge conflict?

Often Git can automatically resolve small and/or simple conflicts, but if not, devleopers will manually need to fix the 
conflicting files and select changes to be ultimately made. Git will let you know when automatic merge has failed, and 
display the type of conflict (e.g. 'content').


