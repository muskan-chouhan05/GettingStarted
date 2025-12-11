# Git Cherry-pick

The `git cherry-pick` command is used to apply a specific commit from one branch onto another branch.  
It is helpful when you want to move only a single commit instead of merging the entire branch.

## 🧩 Why Cherry-pick?
- To apply a particular fix or feature commit to another branch.
- To avoid merging extra unwanted commits.
- To copy selected changes without merging whole branches.

## 📌 Commands

### 1️⃣ Move to the target branch

git checkout <target-branch>


### 2️⃣ Apply a specific commit using cherry-pick

git cherry-pick <commit-hash>


### 3️⃣ If there are conflicts, resolve them and then continue

git cherry-pick --continue


### 4️⃣ To cancel the cherry-pick process

git cherry-pick --abort


## ✔ Example

git checkout main
git cherry-pick a7c9e21


This applies commit **a7c9e21** from another branch to the **main** branch.
