# Collection of research and projects

## Up and running

Clone this repo. There's a link on the repository page, or use the command below.

```
$ git clone git@github.com:biglovisa/women-data-science-projects.git
```

`cd` (Change directory) into the repo

```
$ cd women-data-science-projects
```

### Commit a change

Once you have added to the repository on your local machine, you want to make a so-called commit. You make the commit using `git`.

1. Run the `git status` command to see what the changed files are.

```
$ git status
```

2. Add your changes. The `.` refers to all changed files in the current repository.

```
$ git add .
```

3. Make the commit and add a commit message describing the changes.

```
$ git commit -m "Add git information to readme"
```

4. Push up the changes to the repository

```
$ git push
```

5. Go to the Github repository and see your latest version!

### Working with branches and PRs

With multiple people working on a repository, it's best to work with branches and pull requests to prevent merge conflicts and lost work.

Summarized, the general workflow with branches and pull requests are:

1. Pull the latest changes from the master branch (check your current branch by running `git branch`)

```
$ git pull
```

2. Check out a new branch where you will be doing your work. Give it some name that you can identify it with.

```
$ git checkout -b <my-branch-name>
```

3. Do work, commit your changes (see above), and push it up to your branch.

```
$ git push -u origin <my-branch-name>
```

4. Go to GitHub, and create a new pull request and have your friends review it! Once the review is done, go ahead and merge the pull request, check out the master branch, and pull down your merged changes.

```
$ git checkout -b master
$ git pull origin master
```
