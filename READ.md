# Github configuration   Using vs code 
Here’s a list of the **most commonly used Git commands** with simple explanations:

---

## ✅ **Basic Git Commands**

### 1️⃣ **Setup Configuration**

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

### 2️⃣ **Initialize Repository**

```bash
git init
```

> Creates a new Git repository in the current folder.

---

### 3️⃣ **Clone a Repository**

```bash
git clone https://github.com/user/repo.git
```

> Download a remote repository to your local machine.

---

### 4️⃣ **Check Status**

```bash
git status
```

> Shows changes (staged, unstaged, untracked files).

---

### 5️⃣ **Add Files to Staging Area**

```bash
git add <filename>        # Add a single file
git add .                 # Add all changes
```

---

### 6️⃣ **Commit Changes**

```bash
git commit -m "Commit message"
```

> Saves changes to the local repository.

---

### 7️⃣ **View Commit History**

```bash
git log
```

---

### 8️⃣ **Push Changes to Remote Repository**

```bash
git push origin <branch-name>
```

> Example:

```bash
git push origin main
```

---

### 9️⃣ **Pull Latest Changes from Remote**

```bash
git pull origin <branch-name>
```

---

### 1️⃣0️⃣ **Create a New Branch**

```bash
git branch <branch-name>
```

---

### 1️⃣1️⃣ **Switch to a Branch**

```bash
git checkout <branch-name>
```

---

### 1️⃣2️⃣ **Merge Branches**

```bash
git merge <branch-name>
```

---

### 1️⃣3️⃣ **Delete a Branch**

```bash
git branch -d <branch-name>
```

---

### 1️⃣4️⃣ **Check Remote URLs**

```bash
git remote -v
```

---

### 1️⃣5️⃣ **Remove Remote**

```bash
git remote remove origin
```

---

## ✅ **Bonus: Undo Last Commit (Keep Changes)**

```bash
git reset --soft HEAD~1
```

---

## ✅ **Summary Cheat Sheet:**

| Action          | Command                   |
| --------------- | ------------------------- |
| Initialize repo | `git init`                |
| Clone repo      | `git clone <url>`         |
| Stage changes   | `git add .`               |
| Commit          | `git commit -m "message"` |
| Push            | `git push origin main`    |
| Pull            | `git pull origin main`    |
| Branch create   | `git branch dev`          |
| Switch branch   | `git checkout dev`        |
| Merge           | `git merge dev`           |

---

### 🔽 Want me to give you a **Git Workflow Diagram (visual)** to easily remember push, pull, commit, branch flow?

Reply **"Yes, Git Workflow Diagram"** if you'd like it. 😊

``` bash 

welcome
````
