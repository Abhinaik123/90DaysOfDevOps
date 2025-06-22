Branching Strategies**:

## ✅ Week 4 Challenge – Git & GitHub

### 🔧 Git Commands Used (Tasks 1–4)

```bash
# Task 1: Fork & Clone
git clone https://github.com/Abhinaik123/90DaysOfDevOps.git
cd 90DaysOfDevOps/2025/git/01_Git_and_Github_Basics

# Task 2: Initialize Local Repo & Add File
mkdir week_2_challenge
cd week_2_challenge
git init
echo "My name is Abhijeet Naik. I am learning DevOps." > info.txt
git add info.txt
git commit -m "Initial commit: Add info.txt with basic introduction"

# Task 3: Connect Remote with PAT & Push
git remote add origin https://<username>:<PAT>@github.com/<username>/90DaysOfDevOps.git
git push -u origin main

# Task 4: View Commit History
git log
```

---

### 🌿 Why Branching Strategies Are Important

Branching strategies play a vital role in collaborative software development. Here's why:

1. **📦 Isolating Features and Bug Fixes**
   Branches allow each developer to work on individual features or fixes without affecting the stable codebase.

2. **👨‍👩‍👧‍👦 Facilitating Parallel Development**
   Multiple team members can work on different tasks simultaneously using separate branches.

3. **⚔️ Reducing Merge Conflicts**
   With a clean branching structure (e.g., `main`, `dev`, `feature-*`, `bugfix-*`), code integration becomes smoother and easier to manage.

4. **🔍 Enabling Effective Code Reviews**
   Pull requests created from branches allow reviewers to clearly see changes, suggest improvements, and maintain high code quality before merging.


