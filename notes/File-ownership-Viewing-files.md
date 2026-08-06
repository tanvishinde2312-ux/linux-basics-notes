# 👑 Day 7 – File Ownership & Viewing Files

## 📖 Overview

In Linux, every file has an **owner** and a **group**. The owner usually creates the file and controls its permissions. Linux also provides several commands to view file contents efficiently.

---

# 👤 Changing File Ownership

## 🔹 What is `chown`?

The `chown` command is used to change the **owner** of a file or directory.

> ⚠️ Only the **root user** or a user with **sudo privileges** can change the file owner.

---

## 📝 Syntax

```bash
chown [OWNER] FILE
```

### Example

```bash
sudo chown root hello.sh
```

### Verify Ownership

```bash
ls -l hello.sh
```

### Output

```bash
-rwxr--r-- 1 root sysadmin 647 Dec 20 hello.sh
```

✅ The owner has successfully changed from **sysadmin** to **root**.

---

# 📄 Viewing File Contents

Linux provides multiple commands to read files.

---

## 🐱 cat Command

Displays the **entire contents** of a file.

### Syntax

```bash
cat filename
```

### Example

```bash
cat animals.txt
```

✅ Best for small text files.

---

## ⬆️ head Command

Displays the **first 10 lines** of a file by default.

### Syntax

```bash
head filename
```

### Example

```bash
head alpha.txt
```

Show only the first 5 lines:

```bash
head -n 5 alpha.txt
```

---

## ⬇️ tail Command

Displays the **last 10 lines** of a file by default.

### Syntax

```bash
tail filename
```

### Example

```bash
tail alpha.txt
```

Show only the last 5 lines:

```bash
tail -n 5 alpha.txt
```

---

# 💡 Key Learnings

- 👤 Learned how to change file ownership using `chown`.
- 🔐 Understood that changing ownership requires **sudo** privileges.
- 🐱 Used `cat` to display complete file contents.
- ⬆️ Used `head` to view the beginning of a file.
- ⬇️ Used `tail` to view the end of a file.
- 🔍 Used `-n` option to display a specific number of lines.

---

# 📌 Summary

Day 7 introduced **file ownership** and **file viewing commands**. I learned how to change file owners using `chown` and explored different ways to read file contents efficiently using `cat`, `head`, and `tail`.
