🚀 **Git Cheat Sheet**

1. **Clone a Repository:**
   - To copy a repository from a remote server to your local machine.
     ```bash
     git clone <repository_url>
     ```

2. **Commit Changes:**
   - To save changes made to files in your local repository.
     ```bash
     git add .               # Stage all changes
     git commit -m "Message"  # Commit changes with a descriptive message
     ```

3. **Push Changes to Remote:**
   - To upload your local commits to the remote repository.
     ```bash
     git push origin <branch_name>
     ```

4. **Fetch Remote Changes:**
   - To retrieve changes from the remote repository without merging them.
     ```bash
     git fetch
     ```

5. **Pull Remote Changes:**
   - To retrieve and merge changes from the remote repository into your local branch.
     ```bash
     git pull origin <branch_name>
     ```

6. **Checkout Branch:**
   - To switch between different branches in your local repository.
     ```bash
     git checkout <branch_name>
     ```

7. **Reset Changes:**
   - To undo commits and move the branch pointer to a previous commit.
     ```bash
     git reset --hard <commit_hash>
     ```

8. **Delete Local Branch:**
   - To remove a local branch.
     ```bash
     git branch -d <branch_name>
     ```

9. **Delete Remote Branch:**
   - To remove a branch from the remote repository.
     ```bash
     git push origin --delete <branch_name>
     ```

📝 **Quick Notes:**
- Replace `<repository_url>` with the URL of the repository.
- Replace `<branch_name>` with the name of the branch you are working on.
- Replace `<commit_hash>` with the hash of the commit you want to reset to.

🚨 **Remember:** Replace placeholders with your specific details, and be cautious when using commands that modify history (e.g., reset). If you're new to version control, practice on a test repository before working on important projects.
