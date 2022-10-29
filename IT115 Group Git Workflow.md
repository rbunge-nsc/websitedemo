Use this approach when sitting down to work on your project:

[[#0. Check for any outstanding Pull Requests on Github.]]
[[#1. Update your local repository.]]
[[#2. Starting from the "main" branch, create a new feature branch for your changes.]]
[[#3. Work on your files!]]
[[#4. Commit your finalized changes on your branch and push them to Github.]]
[[#5. If your changes are finished and ready to be merged into "main", create a Pull Request on Github.]]

---

# 0. Check for any outstanding Pull Requests on Github.
Make sure we're not waiting to finalize anyone's changes - if there are any that are ready to be merged in, you'll want to make sure that they are before you start working. This will help us avoid a redundant labor scenario.

# 1. Update your local repository.
Now that we're ready to sit down and work, you'll need to grab all of the changes that other teammates might have made while you were away from your computer. **For our purposes, just do a `git pull`.**

# 2. Starting from the "main" branch, create a new feature branch for your changes.
This is the one of the big reasons you use git - we want to avoid making changes to the master copy of the project until we're absolutely sure our work is ready to be finalized.

Use whatever tool you're most comfortable with to interact with git. The command-line instructions are below, but the verbs should be similar to what you'd find on a git GUI:

```bash
# make sure you're on main to start
git status 
# branch from main to your feature branch
git branch my-feature-branch-name
# switch to your feature branch
git switch my-feature-branch-name
# make sure your feature branch exists on the remote repository
git push --set-upstream origin my-feature-branch-name
```

# 3. Work on your files!
Make whatever changes you need to do on your files using a text editor such as VS Code. Make sure you're saving your changes as you go. 

All of these changes only exist on your feature branch, and none of them will be finalized until you commit the changes in the next step.

# 4. Commit your finalized changes on your branch and push them to Github.
Now that you've done all of your work, you'll need to add all of the changed files to your commit, create a message for the commit, and push it to the remote repository.

```bash
# check which files have been modified
git status
# add your changed files to the new commit
git add my_first_changed_file.html my_other_changed_file.css
# create a commit message that describes what you did
git commit -m "Fixed formatting in my_first_changed_file.html, cleaned up redundant code in my_other_changed_file.css."
# push your changes to the remote repository
git push
```

Now when your teammates start back at step 1, they will pull down all of your changes as well.

# 5. If your changes are finished and ready to be merged into "main", create a Pull Request on Github.
Use the same method that we used in earlier assignments. Add comments to describe what your proposed changes will do, as well as any outstanding issues or concerns. Teammates will check and confirm any outstanding pull requests before they sit down to work.

#git #git-push #git-pull #branching #it115 