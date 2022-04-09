# VITMAS_TASK0
Various  github commands

1.) git add:
This moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.

2.) git branch:
This command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.

3.) git checkout:
In addition to checking out old commits and old file revisions, git checkout is also the means to navigate existing branches. Combined with the basic Git commands, it’s a way to work on a particular line of development.

4.) git clean:
It removes untracked files from the working directory. This is the logical counterpart to git reset, which only operates on tracked files.

5.) git clone:
This creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.

6.) git commit:
It takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.

7.) git commit --amend:
Passing the --amend flag to git commit lets you amend the most recent commit. This is very useful when you forget to stage a file or omit important information from the commit message.

8.) git config:
It is a convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.

9.) git fetch:
Fetching downloads a branch from another repository, along with all of its associated commits and files. But, it doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your project.

10.) git init:
This initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.

11.) git log:
This lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.

12.) git merge:
This is a powerful way to integrate changes from divergent branches. After forking the project history with git branch, git merge lets you put it back together again.

13.) git pull:
Pulling is the automated version of git fetch. It downloads a branch from a remote repository, then immediately merges it into the current branch. This is the Git equivalent of svn update.

14.) git push:
Pushing is the opposite of fetching. It lets you move a local branch to another repository, which serves as a convenient way to publish contributions. This is like svn commit, but it sends a series of commits instead of a single changeset.

15.) git rebase:
Rebasing lets you move branches around, which helps you avoid unnecessary merge commits. The resulting linear history is often much easier to understand and explore.

16.) git rebase -i:
The -i flag is used to begin an interactive rebasing session. This provides all the benefits of a normal rebase, but gives you the opportunity to add, edit, or delete commits along the way.

17.) git reflog:
Git keeps track of updates to the tip of branches using a mechanism called reflog. This allows you to go back to change sets even though they are not referenced by any branch or tag.

18.) git remote:
It is a convenient tool for administering remote connections. Instead of passing the full URL to the fetch, pull, and push commands, it lets you use a more meaningful shortcut.

19.) git reset:
This undoes changes to files in the working directory. Resetting lets you clean up or completely remove changes that have not been pushed to a public repository.

20.) git revert:
This undoes a committed snapshot. When you discover a faulty commit, reverting is a safe and easy way to completely remove it from the code base.

21.) git status:
It displays the state of the working directory and the staged snapshot. You’ll want to run this in conjunction with git add and git commit to see exactly what’s being included in the next snapshot.

22.) git stash:
This command temporarily stores all the modified tracked files.

23.) git tag:
This is used to give tags to the specified commit.

24.) git rm:
This deletes the file from your working directory and stages the deletion.

25.) git diff:
This command shows the file differences which are not yet staged.
