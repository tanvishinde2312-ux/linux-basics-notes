# 📁 File Management in Linux

## 📖 Overview

Linux provides powerful commands to **copy, move, rename, and delete files** efficiently from the command line.

---

# 📋 Copy Files (`cp`)

The `cp` command creates a copy of a file or directory.

### Syntax

```bash
cp SOURCE DESTINATION
```

### Example

```bash
cp /etc/passwd .
```

---

# 🚚 Move & Rename Files (`mv`)

The `mv` command moves files between directories or renames them.

### Syntax

```bash
mv SOURCE DESTINATION
```

### Example

```bash
mv animals.txt zoo.txt
```

---

# 🗑 Remove Files (`rm`)

The `rm` command permanently deletes files and directories.

### Syntax

```bash
rm FILE
```

### Example

```bash
rm linux.txt
```

Delete a directory:

```bash
rm -r Work
```

> ⚠️ **Warning:** Files deleted with `rm` cannot be recovered easily.

---

# 💾 Copy Data (`dd`)

The `dd` command copies data at the bit level.

### Syntax

```bash
dd if=INPUT of=OUTPUT
```

### Example

```bash
dd if=/dev/zero of=/tmp/swapex bs=1M count=50
```

---

# ✨ Commands Learned

```bash
cp
mv
rm
dd
```

---

# 📝 Key Takeaways

- 📂 Copy files using `cp`
- 🚚 Move or rename files using `mv`
- 🗑 Delete files using `rm`
- 💾 Copy data using `dd`
- 🔒 Understand file permissions before managing files

---

## ✅ Summary

Today I learned the essential Linux file management commands that help organize, copy, move, rename, and remove files efficiently.
