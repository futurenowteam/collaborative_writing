# Collaborative Writing

Today you are going to write a short story but unfortunately, because of time constraints, you’ll need to enlist the help of your teammates.

Everyone in the group is going to clone this repository and one by one each of you will write the next sentence. In the end you will have a story that starts off with the sentence we give you and finishes with what you and your group writes.

This assignment is going to teach you how to collaborate using git on GitHub. This means cloning a repository, pulling the changes that other people have made, and pushing your changes up. You might even come across merge conflicts.

## Assignment
1. One person in the group forks this repository.
2. Everyone in the group clones that person's repository.
3. One person pulls the most recent changes, edits the text file, writes the next sentence, makes a commit, and pushes the changes up.
4. Repeat Step 3 until everybody has done it.
5. Celebrate! You just learned the basics of git 🎉

## Important Git Commands

### Git Workflow
```
# creates new git repository
$ git init

# stages changes to files
$ git add .

# stages changes to all files (including deleted files)
$ git add --all

# shows status of files
$ git status

# creates a new commit (a snapshot in time) with associated message
$ git commit -m "<message>"

# shows history of commits
$ git log
```

### Remote Repositories (Github)
```
# maps server url to "origin"
$ git remote add origin <server url>

# pulls a specific branch to local repo
$ git pull <branch name>

# pushes local repo to remote repo
$ git push origin <branch name>

# copies a new remote repo to computer
$ git clone <server url>
```

###Branching
```
# shows all branches
$ git branch

# creates a new branch with <branch_name>
$ git branch <branch_name>

# switches to <branch_name>
$ git checkout <branch_name>

# creates a new branch with <branch_name> and switches to it
$ git checkout -b <branch_name>

# merges (copies) commits from <branch_name> into current branch
$ git merge <branch_name>
```

### Additional Resources
[Collaborating at GitHub Help](https://help.github.com/categories/collaborating/)

[Team Collaboration with GitHub at Tuts+](http://code.tutsplus.com/articles/team-collaboration-with-github--net-29876)
