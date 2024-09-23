# test1
tét commits tét2
## Update latest change from the main branch
```bash
# Fetch the latest changes from the remote repository:
git fetch origin
# Switch to your branch (if you are not already on it):
git checkout your-branch-name
# Rebase your branch onto the main branch
git rebase origin/main
# Resolve any conflicts if prompted
git add .
git rebase --continue
# Push your updated branch to the remote repository
git push origin your-branch-name
```


## Create a new branch and push into remote repository
To create a new branch, switch to it, and publish it to a remote repository, you can use the following Git commands:

1. **Create a new branch**:
   ```sh
   git branch <branch-name>
   ```

2. **Switch to the new branch**:
   ```sh
   git checkout <branch-name>
   ```

   Alternatively, you can combine the above two steps into one command:
   ```sh
   git checkout -b <branch-name>
   ```

3. **Publish the branch to the remote repository**:
   ```sh
   git push -u origin <branch-name>
   ```

### Example:

Let's say you want to create a new branch named `feature-branch`, switch to it, and publish it to the remote repository.

1. **Create and switch to the new branch**:
   ```sh
   git checkout -b feature-branch
   ```

2. **Publish the branch to the remote repository**:
   ```sh
   git push -u origin feature-branch
   ```

### Explanation:

- `git checkout -b <branch-name>`: This command creates a new branch named `<branch-name>` and switches to it.
- `git push -u origin <branch-name>`: This command pushes the new branch to the remote repository and sets the upstream tracking reference, so future `git push` and `git pull` commands will know which remote branch to interact with.

By following these steps, you can create a new branch, switch to it, and publish it to the remote repository.
