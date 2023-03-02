# Git Branch

<img src="./images/branches.svg" alt="branches" />

## What is a branch ?

Git branches is a pointer to a special state of your changes that represent them like :

-  new feature
-  new Version
-  a bug fix
-  ...

## How to use

-  See list of local branches

   ```bash
   git branch
   ```

-  See list of remote branches

   ```bash
   git branch -a
   ```

-  Create a new branch with name of <branch>

   ```bash
   git branch <branch>
   ```

-  Delete a branch with name of <branch>

   ```bash
   git branch -d <branch>  // Safe Delete
   git branch -D <branch>  // Force Delete
   ```

-  Rename the current branch to <branch>

   ```bash
   git branch -m <branch>
   git branch -M <branch>
   ```
