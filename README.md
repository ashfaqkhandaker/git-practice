# Git & GitHub Practice Exercise

## Objective

The objective of this lab was to learn the basic workflow of Git and GitHub by creating a repository, adding a C++ program, cloning the repository to a local computer, modifying the source code, and uploading the changes back to GitHub using Git commands.

---

## Tasks Performed

### Step 1: Created a GitHub Repository
- Logged into GitHub.
- Created a new public repository named **git-practice**.

### Step 2: Added the Initial C++ File
- Created a file named `main.cpp`.
- Added the provided C++ source code.
- Committed the file with the message:
  ```
  Initial commit
  ```

### Step 3: Cloned the Repository
- Copied the repository URL.
- Cloned the repository to the local computer using:
  ```bash
  git clone <repository_url>
  ```
- Entered the project directory:
  ```bash
  cd git-practice
  ```

### Step 4: Checked Repository Status
Verified that the working directory was clean using:
```bash
git status
```

### Step 5: Modified the Program
Updated the following information inside `main.cpp`:
- Name
- Student ID
- Section
- Added an additional personal information field

### Step 6: Viewed Changes
Checked the modifications using:
```bash
git diff
```

Verified the modified file:
```bash
git status
```

### Step 7: Staged the Changes
Added the updated file to the staging area:
```bash
git add main.cpp
```

### Step 8: Committed the Changes
Created a new commit with:
```bash
git commit -m "Updated student information"
```

### Step 9: Pushed the Changes
Uploaded the latest commit to GitHub using:
```bash
git push
```

---

## Git Commands Used

```bash
git clone
git status
git diff
git add
git commit
git push
```

---

## Learning Outcomes

After completing this lab, I learned how to:

- Create a GitHub repository.
- Add and manage files on GitHub.
- Clone a remote repository to a local machine.
- Track file changes using Git.
- Stage and commit changes.
- Push local commits to a remote GitHub repository.
- Understand the basic Git workflow used in software development.

---

## Conclusion

This lab provided practical experience with Git and GitHub. It helped me understand how version control works and how developers collaborate by tracking, committing, and pushing code changes using Git.
