# Learning GitHub
Learning and testing GitHub with Git.

## Useful links

Adding a project to GitHub using the command line:
https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

Cloning a repository:
https://help.github.com/articles/cloning-a-repository/

Writing and formatting syntax:
https://help.github.com/articles/basic-writing-and-formatting-syntax/

## Basic steps
```
$ git clone or $ git init
$ git add
$ git commit
$ git push
```

## Git Bash

**Setting user name:**
```
$ git config --global user.name "Github Username"
```

**Setting user email:**
```
$ git config --global user.email "Github Email"
```

**Copy repo to local:**
```
$ git clone url of repo
```

**Create a new repo in local folder:**
```
$ git init
```

**Create a new file local:**
```
$ touch filename
```

**Remove file local and from the repo:**
```
$ git rm filename
```

**Remove file only from the repo and not local:**
```
$ git rm --cached filename
```

**Add file to the staging area:**
```
$ git add filename
```

**Storing file changes from the staging area in the repository with a message:**
```
$ git commit -m "Message"
```

**Updating repo with the local changes:**
```
$ git push origin branch_name
```

**Inspecting content of the working directory and staging area:**
```
$ git status
```

**Showing list of commits:**
```
$ git log
```

**Change directory:**
```
$ cd /path/folder/ *Example: cd /c/Github/*
```

**Change directory if empty or ():**
```
$ cd "Folder ()" *Example: cd "Program Files (x86)"*
```

**See content of a directory:**
```
$ ls
```

