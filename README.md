# My-First-Repo
This is my first repo.
# Project Name

## Branching Guide

This project follows a branching strategy to ensure smooth collaboration and version control. The following guide outlines how to create a new branch, which is useful when adding a new feature, fixing a bug, or making isolated changes.

### How to Create a New Branch in Git

1. **Navigate to the Project Directory**:
   - Open your terminal and use the `cd` command to navigate to the project folder:
     ```bash
     cd /path/to/your/project
     ```

2. **Ensure You Are on the Main Branch**:
   - Before creating a new branch, ensure you are on the main branch (or the primary branch you are branching from). Use:
     ```bash
     git checkout main
     ```

3. **Create and Switch to a New Branch**:
   - To create a new branch and switch to it immediately, use the following command:
     ```bash
     git checkout -b <branch-name>
     ```
   - Replace `<branch-name>` with a meaningful name that reflects the work you will be doing (e.g., `feature-login`, `bugfix-header`, `docs-update`).

4. **Verify the Branch Creation**:
   - After creating the branch, you can verify which branch you are currently on by running:
     ```bash
     git branch
     ```
   - This command will list all branches and show the active branch with an asterisk (`*`).

5. **Start Making Changes**:
   - Once on your new branch, you can begin editing files, adding features, or making other modifications.

6. **Commit and Push Changes**:
   - After making changes, add and commit them:
     ```bash
     git add .
     git commit -m "Add description of your changes"
     ```
   - Push the new branch to the remote repository:
     ```bash
     git push origin <branch-name>
     ```

7. **Submit a Pull Request**:
   - Once your branch is pushed, go to the GitHub repository to create a pull request. This process allows other team members to review and merge the changes.

---

### Purpose of Branch Creation

Branching allows multiple developers to work in parallel without interfering with the main project code. Each branch represents a separate line of development, enabling isolated work on specific features or bug fixes.

---

Add any additional project-specific details to this README to make it more informative for team members working with branches. Let me know if you need any other modifications!
