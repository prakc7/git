# Steps to follow:

```bash
echo "# git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main (M denotes Master branch)
```

---

# Connecting to GitHub

- Either using https or ssh

- We need to authorise each time if using https

```bash
git remote add origin https://github.com/user-name/repository-name.git
```

- We need to set ssh at once for our machine

```text
git@github.com:user-name/repository-name.git
```

---

# Setting Up SSH Keys

- Using cmd

```bash
ssh-keygen -o 
```

Go to .ssh

```bash
cd .ssh
ls -a
cat id_rsa.pub
```

- Copy the key 

Go to your GitHub profile settings

In Access section
Go to SSH and GPG Keys

- Add new key
- Paste the Key

---

# Push to GitHub

```bash
git push -u origin main
```

- -u denotes upstream and main can be other branch

---

# Push the Other files

```bash
git add filename
git commit -m "your-message"
git push origin main
```

---

# Cloning the Repository

```bash
git clone github-repo-link
```

---

# Checking for origin

```bash
git remote -v
```

---

# Check for All Past Tags

```bash
git tag
```

---

# Adding tag

```bash
git tag -a your-tag-name -m "your-message"
```

- Tags the last commit

---

# Tag Description

```bash
git show your-tag-name
```

---

# Push tags to GitHub

```bash
git push origin your-tag-name
```

---

