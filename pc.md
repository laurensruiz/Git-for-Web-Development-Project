## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

2. What is the difference between Git and GitHub?
Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

3. Why do we create a branch?
You can then work on this new branch in isolation from changes that other people are making to the repository. 

4. What is the purpose of a Pull Request?
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
$ git checkout <branch>

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
- git fetch: fownload all changes from remote branch but does not integrate into HEAD
- git merge: merges current branch into current HEAD
- git pull: download changes and directly merge/integrate into HEAD

7. What is a merge conflict?
Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.

8. How do you resolve a merge conflict?
To resolve a merge conflict, you must manually edit the conflicted file to select the changes that you want to keep in the final merge. 