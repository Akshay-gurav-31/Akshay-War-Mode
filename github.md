# 📚 Git & GitHub Learning Notes

---

# 📅 Day 1 — 🐙 Git & GitHub Basics

## 1. What is GitHub?

GitHub is a platform used to store, manage, and share code online.
It is built on Git, which tracks changes in your code.

---

## 2. Key Concepts

### 2.1 Repository (Repo)

A repository is a project folder that contains:

1. Code files
2. Project data
3. Version history

---

### 2.2 Commit

A commit is:

1. A saved snapshot of your code
2. Stored with a message

---

### 2.3 Branch

A branch is used to:

1. Work on new features
2. Keep main code safe

---

### 2.4 Clone

Cloning means:

1. Copying a project from GitHub
2. Bringing it to your local system

---

### 2.5 Push & Pull

1. Push → Upload code to GitHub
2. Pull → Download latest updates

---

### 2.6 Fork

Fork means:

1. Creating your own copy
2. Of someone else’s repository

---

### 2.7 Pull Request (PR)

A Pull Request is:

1. A request to merge code
2. Reviewed before approval

---

## 3. Interview Questions & Answers

### 3.1 Basic

**1. Difference between Git and GitHub?**
Git tracks changes locally, GitHub stores code online.

**2. What is a repository?**
A project folder with code and history.

**3. What is a commit?**
A saved version of changes.

**4. Why use branches?**
To work safely without affecting main code.

**5. Push vs Pull?**
Push uploads, pull downloads.

---

### 3.2 Medium

**6. What is merge?**
Combining changes from one branch into another.

**7. What is a merge conflict?**
When Git cannot decide between changes.

**8. Fork vs Clone?**
Fork = online copy, Clone = local copy.

**9. What is a pull request?**
A request to merge changes.

**10. What is `.gitignore`?**
A file that ignores unnecessary files.

---

### 3.3 Practical

**11. How to create a repository?**
Create it on GitHub and connect your project.

**12. How to upload code?**
Save changes and push to GitHub.

**13. How to resolve conflicts?**
Fix manually and commit again.

**14. How do teams collaborate?**
Using branches and pull requests.

---

## 4. Summary

1. Git → Tracks changes
2. GitHub → Stores code online
3. Repository → Your project workspace

---

# 📅 Day 2 — 🔧 Git Commands (Hands-on)

## 🔧 Commands Learned

### 1. Initialize Repository

```bash
git init
```

Start a new Git repository.

---

### 2. Check Status

```bash
git status
```

Check changed, staged, and untracked files.

---

### 3. Add Files (Staging Area)

```bash
git add file.txt
git add .
```

Add files to staging area.

---

### 4. Commit Changes

```bash
git commit -m "your message"
```

Save staged changes with a message.

---

### 5. Unstage Files

```bash
git reset
```

Remove files from staging area.

---

## 🔄 Workflow

```text
Write Code → git add → git commit
```

---

## 🧠 Key Understanding

* Staging Area = selection before commit
* Only added files get committed
* You can commit files separately or together

---

## 📌 Final Summary

* `git add` → select files
* `git commit` → save changes
* Git tracks your project step-by-step

---
