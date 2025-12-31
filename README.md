# Text Content vs Document Write Text

# textContent
`textContent` we can change inside text.

### Example:
```bash
outputP.textContent = `${a} is big`
```

# innerText
`document.innerText = "Yash "`  we also this method change inside text.

### Example:
```bash
outputP.innerText = c;
```

# 📘 Git & GitHub Basics – Add Files and Collaborate with Friends

This guide helps you **learn Git from zero**, including how to **add files**, **push to GitHub**, and **collaborate with friends** step by step.

---

## 🔹 What is Git?

**Git** is a version control system used to:
- Track code changes
- Work with multiple developers
- Manage project history safely

---

## 🔹 What is GitHub?

**GitHub** is an online platform to:
- Store Git repositories
- Share code with others
- Collaborate using pull requests

---

## 🛠 Prerequisites

- Install Git → https://git-scm.com
- Create GitHub account → https://github.com
- Install VS Code (recommended)

---

## 🚀 STEP 1: Configure Git (One Time)

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## 📂 STEP 2: Create New Git Repository (Local)
Go to your project folder:

```bash
cd your-project-folder
```

Initialize Git:
```bash
git init
```

## ➕ STEP 3: Add Files to Git

Check file status:

```bash
git status
```

Add all files:

```bash
git add .
```

## 💾 STEP 4: Commit Changes

```bash
git commit -m "Initial project commit"
```

## 🌍 STEP 5: Push Project to GitHub
1️⃣ Create new repository on GitHub (NO README)
2️⃣ Connect local repo to GitHub

```bash
git remote add origin https://github.com/username/repository-name.git
```

3️⃣ Push code

```bash
git branch -M main
git push -u origin main
```

## 🤝 STEP 6: Collaborate with Friend (Method 1 – Add Collaborator)
👤 Owner (You)

 - Go to GitHub repository

 - Settings → Collaborators

 - Add friend’s GitHub username

 👤 Friend

 ```bash
 git clone https://github.com/username/repository-name.git
```

## 🔁 STEP 7: Friend Makes Changes

```bash
git status
git add .
git commit -m "Added new feature"
git push
```

## 🔄 STEP 8: You Pull Friend’s Changes
```bash
git pull
```

## 🌿 STEP 9: Branching (Safe Collaboration)

Create new branch:

```bash
git branch feature-login
git checkout feature-login
```

Or shortcut:

``` bash
git checkout -b feature-login
```

Push branch:
```bash
git push origin feature-login
```

## 🔀 STEP 10: Pull Request (Best Practice)

 - Friend pushes branch

 - Open GitHub → Pull Request

 - Owner reviews code

 - Merge into main


## ⚠ Common Git Commands
```bash
| Command    | Purpose           |
| ---------- | ----------------- |
| git status | Check file status |
| git add .  | Stage files       |
| git commit | Save changes      |
| git pull   | Get latest code   |
| git push   | Upload changes    |
| git clone  | Download repo     |
| git branch | Show branches     |
```

## ✅ Best Practices

 - Always use branches

 - Commit small changes

 - Write clear commit messages

 - Pull before push

 - Use Pull Requests