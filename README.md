# Git-Gud

- Dodging knowledge gaps

- Creating a Github profile acount
- SSH

<br>

- What is a README?
- Good readme's
- why not neglect readme

<br>
- Git commands
<br>

<br>

Git init

Initializes a new Git repository in the current directory. This command is used when you want to start tracking a project with Git.

<br>


```sh
git init
```

<br>

Git clone

Creates a local copy of a remote repository. This is typically the first command you use when collaborating on a project, as it copies the entire history of the project from a server to your machine.

<br>

```sh
git clone
```

<br>

Git status

Displays the current state of the working directory and staging area. It shows which files are changed but not yet staged, which are staged for commit, and which are not being tracked by Git.

<br>

```sh
git status
```

<br>

Git restore

Restores changes in the working directory or the staging area to their last committed state. It’s used for discarding local modifications or un-staging changes that haven’t been committed yet.

<br>

```sh
git restore "filename"
```
<br>

Git add

Adds the specified file(s) to the staging area. This means that you are preparing the file to be committed in the next commit. Use git add . to stage all changes.

```sh
git add
```

```sh
git add .
```

```sh
git add "filename"
```

```sh
git add *
```
<br>

Git commit

Commits the changes in the staging area to the repository with a message describing what has been changed. Each commit represents a snapshot of the project at that point in time.

<br>

```sh
git commit -m "good description please - you tank me later"
```

<br>

Git push

Sends your commits to a remote repository (e.g., GitHub or GitLab). This command is used to share your work with others by pushing your local commits to the central repository.

<br>

```sh
git push 
```

```sh
git push origin branchname
```

```sh
git push origin branchname:main
```

<br>

Git pull

Fetches changes from the remote repository and integrates them into your current branch. This command is essentially a combination of git fetch (to get the changes) and git merge (to merge them into your current branch).

<br>

```sh
git pull
```
<br>

Git rm

Removes files from the working directory and the staging area in Git. It’s used to delete files from your project and ensure that the removal is recorded in the next commit. If the file has already been committed, this will also remove it from the commit history. If you want to stop tracking a file without deleting it locally, use the --cached option.

```sh
git rm "filename"
```

```sh
git rm untracked-files
```

```sh
git rm --cached <file>
```


<br>

<br>

Git log

Displays a log of all commits in the current branch, showing the commit history. You can use options like --oneline to view a more compact log.

<br>

```sh
git log
```

<br>

<br>

Git branch

Lists all local branches in the repository, and with options, can create (git branch <name>) or delete (git branch -d <name>) branches. Branching is a key feature in Git, allowing you to work on multiple versions or features in parallel.

<br>

```sh
git branch
```
Git checkout <branch>

Switches to the specified branch or commit. It’s used for moving between different branches in your repository, allowing you to work on different features or versions of your project. Starting from Git 2.23, it is recommended to use git switch for changing branches.

```sh
git checkout <branch>
```
<br>

Git merge <branch>

Merges the specified branch into the current branch. This is how you combine the work from different branches, typically after development on a feature is complete.

<br>

```sh
git merge <branch>
```

- Fork
- Pull-request
- - Doing your first pull request
- Contributions
- branc
- checkout, branch, branches in general
