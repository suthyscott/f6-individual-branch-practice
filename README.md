# f6-individual-branch-practice

Create a repo on GitHub. 

Create a folder locally and add an index.html file 

Add, commit, and then connect to the remote repo and push. 

Pretend like the html file we just made is really complicated and we don't want to mess it up. We're going to create a new branch to work on by running 
```
git checkout -b styles/main-styling
```

To go back to the main branch we run this command: 

```
git checkout main
```

Let's go back to the style branch and then run git push. It will tell us that our branch has no upstream branch and give us a command to make one. Let's copy and run that command and then push up again. 

In GitHub we should now see that we have two branches, and it should give us an option to compare them and make a pull request. Let's do that so we can merge our style branch into our main branch. 

Now that we've merged that in, let's go back to our local main branch and make sure it reflects those changes by running ``` git fetch ``` to check for changes, and then ``` git pull ``` to add them to our local repo. 


## Branches in group projects. 

Make a repo and send them all a link to view it. Pick a student and invite them to the group repo as a collaborator, and thave them clone the project. 

Have all the other students fork and then clone it, then add a js file with a console.log of their name. 

Have your student collaborator add their name to the index.html file. 

Show how you don't have the student collaborator's changes yet, and pull them down. Show how that works. 

To demonstrate conflicts, have the SC add another change at the same time as you added yours. Have them push up first, and show what happens (conflict errors) when you try to push up on the same branch. 

To resolve these conflicts, make a new branch. Make a pull request and show how to resolve the conflicts in GitHub and merge it in. 

For the students who forked and cloned, make sure they've added and pushed their changes. Explain that in an open source project you'll need to for and clone the repos. 

Have them create a new pull request to add their repo to your base repo. Then show you merging the pull requests in and how it updates the original repo. Now you can see and pull down the changes made by them in their forked repos. 