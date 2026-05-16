# Working with git

Open the working directory.

---

# Check for the Status

```bash
git status
```

---

# Initialise the Repository

```bash
git init
```

Re-check:

```bash
git status
```

You may see:
On branch master/main (By default, branch = master/main)
No commits yet

- Better to use:

```bash
git init -b main (Branch = main at initialisation)
```

---

# Make files
- These files are untracked by git by default.

---

# Track files (Staging)

```bash
git add filename
```

- For all files in the directory

```bash
git add .
```

Re-check:

```bash
git status
```

File name becomes green that mean it is now been tracked by git.

- But, this is not commited till now. That means the changes are not saved to git history.

---

# Unstage 

- Untrack files 

```bash
git rm --cached filename
```

---

# Check for logs

- All past commits

```bash
git log
```

or

- All past commits in separate lines 

```bash
git log --pretty=oneline
```

---

# Commit

- -m defines a clear message for the commit

```bash
git commit -m "your-message"
```

- all commits have uniquely identified code of 40 characters of which 7 are visible to us next to the commit.

Re-check:

```bash
git status
```

You may see:
On branch main
noyhing to commit, working tree clean

- Re-check: git log

you may see:
commit id (HEAD-> branch-name)
Author: username email
Date: Day Month Date Time Year Time-Zone

Commit message

---

# Changes in files

- If you modify anything inside the directory

Re-check:

```bash
git status
```

You may see:
On branch main
modified: filename

or if you added new files then,
On branch main
Untracked files filename

---

# Update files

```bash
git add "filename"
```

- Commit and stage with a single command

```bash
git commit -a -m "your-message"
```

---

# See the Exact changes (Before Staging)

```bash
git diff
```

---

# See the Exact Changes (After Staging)

```bash
git diff --staged
```

---

# Remove files (After commit)

```bash
git rm --cached filename
```

- Then commit:

```bash
git commit -m "your-message"
```

---

# Deleting branch

```bash
git branch -d branch_name
```

- If not merged in your local main branch:

```bash
git branch -D branch_name
```

---

# MarkDown file
Git-featured file with extension .md
- Used to write documentations (More attractive text-files)

---

