# Creating a Branch

- Either using switch or checkout

```bash
git switch -c branch-name
git checkout -b branch-name
```

---

# Check for Branches

```bash
git branch
```

- (*) denotes the current branch you are at.

```bash
git branch --all
```

- it gives all local branches and remote branches at last.

---

# Switching between Branches

- Either using switch or checkout 

```bash
git switch branch-name
git checkout branch-name
```

---

# Switching to Previous Branch

```bash
git switch -
```

---

# Deleting a Branch

```bash
git push origin --delete branch-name
```

- Then to delete locally:

- But, at first you have to switch your branch:

```bash
git switch branch_name(to which you want to switch)
```  

```bash
git branch -d branch_name
```

- If not merged into your local main branch yet:

```bash
git branch -D branch_name
```

---

# Push the Branch

```bash
git push origin branch-name
```

---

# Merge the Branches

```bash
git pull origin main
git switch main
git merge branch-name
git push origin main
```

---

