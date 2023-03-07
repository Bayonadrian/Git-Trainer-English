In this step I will show you how to create branches within git, normally when you work with other developers you need to do it online, through the github repository and through branches so that each developer can work on their own branch without constantly altering the main branch and therefore both the complete project. Branches are created using the command:

-git branch <name>

In the "name" space you must enter the name of your branch. Later if you want to use this branch you must use the command:

-git checkout <name>

Once again in the "name" space, the name of the branch must be used. If you want to see which branch you are in, you can use the command:

-git branch

If you want to merge the content of the branches to the master branch you must use the command:

-git merge <branch>

Using the branch name instead of <branch>, in this way it is recommended to pull the information from the other branch into the "master" branch, in this way it is recommended to follow these steps:

-git checkout master

Then inside the "master" branch do the following:

-git merge <branch>

If the procedure were reversed, inside the <branch> branch, pulling information from the "master" branch, then the "master" branch would be left out.

-> Continue at /stepSix(remote, push, pull)