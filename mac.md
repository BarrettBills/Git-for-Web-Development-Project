## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? Git is an Open Source Distributed Version Control System.
2. What is the difference between Git and GitHub? Git is the software. GitHub is a cloud-based git hosting service.
3. Why do we create a branch? Creating a branch allows you to isolate your work that is being done from other team members.
4. What is the purpose of a Pull Request? It compares your student branch work against the fork created in the beginning.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. Use git checkout <branch name>
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? Git fetch downloads all changes from the remote branch but doesn't integrate into the HEAD. Git merge merges your branch into the current HEAD branch. Git pull downloads changes and directly merges into the HEAD branch.
7. What is a merge conflict? A merge conflict occurs when two programmers have edited the same code in a file and attempted to merge them or if one programmer deleted a file while the other programmer was editing it.
8. How do you resolve a merge conflict? To resolve the merge conflict, simply make any necessary changes so that the two commits are not the same. You can also git merge --abort which would take you back to the original state before the merge began.
