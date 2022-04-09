
# ****BASIC GIT COMMANDS****

Git is distributed version-control system for tracking changes in any set of files. Here are the few basic commands used in git.


# *git int*

 This command turns a directory into an empty Git repository 


```{r setup, include=FALSE}
            git init [repository name]
```

# *git config*

The command sets the author name and email adress respectively to be used with the commits.


```{r setup, include=FALSE}
        git config -global user.name "[name]"
```
```{r setup, include=FALSE}
       git config -global user.email "[email]"
```



# *git add*

The following command adds a file to the staging area.
```{r setup, include=FALSE}
                git add [file]
```


The following command adds one or more to the staging area.
```{r setup, include=FALSE}
                  git add *
```

# *git commit*

This command records or snapshots the file permanently in the version history.
```{r setup, include=FALSE} 
   git commit -m "[Type in the commit message]"
```


This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
```{r setup, include=FALSE}
              git command -a
```

# *git status*

This command returns the current state of the repository.
```{r setup, include=FALSE}
                 git status
```

# *git branch*

To determine which branch the local repository is on, add a branch, or delete a branch.
```{r setup, include=FALSE}
                 git branch
```
```{r setup, include=FALSE}
         git branch [branch name]     
         (Creates a new branch)
```
```{r setup, include=FALSE}
            git branc -d [branch name]  
           (Deletes the feature branch)
```

# *git checkout*

To start working in a different branch, use git checkout to switch branches.
```{r setup, include=FALSE}
                 git checkout
```

# *git merge*

Integrate branches together.
```{r setup, include=FALSE}
            git merge [branch name]
```


# *git remote*

To connect a local repository with a remote repository.
```{r setup, include=FALSE}
git remote add [variable name] [remote server link]
```

# *git clone*

To create a local working copy of an existing remote repository.
```{r setup, include=FALSE}
                 git clone[url]
```

# *git pull*

To get the latest version of a repository run git pull. 
```{r setup, include=FALSE}
          git pull [Repository Link]
```


# *git push*

This command sends the committed changes of master branch to your remote repository.
```{r setup, include=FALSE}
          git push [variable name] master
```


This command sends the branch commits to your remote repository.
```{r setup, include=FALSE}
          git push [variable name] [branch]
```



This command pushes all branches to your remote repository.
```{r setup, include=FALSE}
          git push -all [variable name] 
```


This command deletes a branch on your remote repository.
```{r setup, include=FALSE}
    git push [variable name] :[branch name]
```

# *git rm*

This command deletes the file from your working directory and stages the deletion.
```{r setup, include=FALSE}
                 git rm [file]
```


# *git log*

This command is used to list the version history for the current branch.
```{r setup, include=FALSE}
                    git log
```

# CHEAT SHEET FOR MARKDOWN SYNTAX


Link :- <mark> https://www.markdownguide.org/cheat-sheet/ </mark>
