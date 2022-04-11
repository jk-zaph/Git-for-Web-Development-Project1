## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
    Git is a system that tracks and stores the history of content; what updates have been made, the different versions of it, etc. There are two different versions of Git history, the local version, which is on the developer's computer, and the remote version, which is saved on a server.

2. What is the difference between Git and GitHub?
    The difference between Git and GitHub is that, git is the control system that remembers the history of content, and Github is a company that keeps the content on a cloud server, making it easier to access the content's history and easier to collaborate with others.

3. Why do we create a branch? 
    We create a branch so that the main source of the code is not edited for every modification, and so that it's easier for different people working on the same project to work in their own space.

4. What is the purpose of a Pull Request?
    The pull request "pulls" the main version of git that is on the remote server to the local version.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
    To switch between different branches, you would use the command `git checkout` followed by the branch you want to go to.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    `git fetch` is used to download(fetch) all the objects and content from a repository, and see what changes has been made over time.
    `git merge` is when you want to merge all branches and the main source into one.
    `git pull` takes the local version and pulls it into the remote version, so that the remote matches the changes made on the local file, or content.

7. What is a merge conflict?
    A merge conflict is when two or more developers try to edit the same file or content.
8. How do you resolve a merge conflict?
    You can resolve a merge conflict by using different branches, and then using `git merge` to combine the separate branches with the main source.