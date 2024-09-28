# GitProject-Week1

Project Structure

tasks.txt: A text file that serves as the task database, where tasks are added, removed, or updated during the project.

Steps and Git Commands Used#

1-Set Up the Repository

1.1. git init task-manager

1.2 cd task-manager

2-Create tasks.txt to serve as the task database:

2.1 echo "- Learn Git basics" > tasks.txt

2.2 echo "- Set up Git repository" >> tasks.txt

2.3 git add tasks.txt

2.4 git commit -m "solve question 2b"

3. Create Branches and Work on Features
   
3.1git checkout -b feature/add-tasks

3.2 echo "- Learn Git branching" >> tasks.txt

3.3git add tasks.txt

3.4 git commit -m "solve question 3b "

4 Create a branch to remove tasks:

4.1git checkout -b feature/remove-tasks

4.2 remove some tasks

4.3 git add tasks.txt

4.4 git commit -m "solve question 3d"

5 Merge Branches and Handle Conflicts

5.1 git checkout master

5.2 git merge feature/add-tasks

5.3 git checkout master

5.4 git merge feature/remove-tasks

6 Use Git Rebase

6.1 git checkout -b feature/update-tasks

6.1 git checkout master

6.2 git rebase feature/update-tasks

7. Reverting to Previous Commits
   
7.1 git revert 5d1f825e and then new commit will be added

8. Working with a Remote Repository
   
8.1 git remote add origin <https://github.com/Mohammedalqaydi/GitProject-Week1.git>
   
8.2 git push -u origin master

This project serves as a practice to apply various Git concepts such as branching, merging, conflict resolution, rebase, and cherry-picking. It also covers remote repository management.





