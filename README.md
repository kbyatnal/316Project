# 316 Project - Git Guidelines

While working on this project, we will be working on our own branches and pull requesting to master whenever we feel that our changes are worth adding to the current product. You should NEVER push directly to master.

In order to make a branch, navigate to master branch locally and then pull from master to make sure your local master branch is updated. Then make a branch from that and name it something clear and use that as your working branch. It is completely fine for two people to work on the same branch (other than master), and it is also possible to make branches off of other branches.
- When working on your branch, you should commit frequently with titles that explain what you have changed. I.e. 'worked on search stuff' is bad. 'Added options to search algorithm and button to show advanced options' is good. You don't need to push after every commit. Just push when you have finished something significant, or if someone else needs to use what you've been working on.

When you are ready to add your changes to master, first pull from master into your branch to make sure your branch is updated and resolve any merge conflicts. Then create a pull request to master, but do not merge immediately. In order to make sure our master branch stays clean we will be doing code reviews prior to merge. This means that whenever someone wants to add changes to master, someone else in the group will look through their changes and make sure everything looks reasonable. Obviously if multiple people are working on the same part of the project they should do the code reviews for each other. 
- If you find problems while code reviewing, you can highlight and comment on specific pieces of code. Or if you are sitting next to them, just punch them and tell them they suck.
- If you need to make changes to your pull request, just push to the branch from which you created the pull request and it will automatically update.
- If everything looks good just add a comment saying it is ready for them to merge (you can also make a thumbs up in git comments with ':+1:').
