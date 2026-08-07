# 📸 Day 8 – File Management Practice

> **Topic:** Copying, Moving & Removing Files in Linux  
> 📚 **Course:** Cisco Networking Academy – Linux Unhatched

---

## 🎯 Learning Objectives

Today I learned how to:

- 📄 Copy files using `cp`
- 💾 Create a file using `dd`
- 📂 Move files and directories using `mv`
- ✏️ Rename files
- 🗑️ Remove files and directories using `rm`
- 🔍 Verify operations using `ls`

---

# 🖼️ Practical Screenshots

## 📄 1. Copying Files (`copying-files.png`)

### Commands Used

```bash
cd ~/Documents
cp /etc/passwd .
ls

cd ~
dd if=/dev/zero of=/tmp/swapex bs=1M count=50
```

### ✔ Outcome

- Copied `/etc/passwd` to the current directory.
- Verified the copied file using `ls`.
- Created a **50 MB** file using the `dd` command.

---

## 📂 2. Moving & Renaming Files (`moving-files.png`)

### Commands Used

```bash
cd ~/Documents

mv people.csv Work
ls Work

mv numbers.txt letters.txt alpha.txt School
ls School

mv animals.txt zoo.txt
ls
```

### ✔ Outcome

- Moved files between directories.
- Moved multiple files using a single command.
- Renamed `animals.txt` to `zoo.txt`.

---

## 🗑️ 3. Removing Files (`removing-files.png`)

### Commands Used

```bash
cd ~/Documents

rm linux.txt
ls linux.txt

rm Work
rm -r Work
ls Work
```

### ✔ Outcome

- Deleted a file using `rm`.
- Removed a directory using `rm -r`.
- Verified successful deletion.

---

# 🛠️ Commands Practiced

| Command | Purpose |
|---------|---------|
| `cp` | Copy files |
| `dd` | Copy data / Create files |
| `mv` | Move or rename files |
| `rm` | Remove files |
| `rm -r` | Remove directories recursively |
| `ls` | Verify file operations |

---

# 📚 Key Takeaways

- ✅ `cp` creates copies without affecting the original file.
- ✅ `mv` moves files and can also rename them.
- ✅ `rm` permanently deletes files.
- ✅ `rm -r` removes directories and all their contents.
- ✅ `dd` is a powerful utility for low-level copying and disk operations.

---

## 🚀 Day 8 Progress

**Status:** ✅ Completed

> Every Linux command practiced today strengthens my command-line skills and builds a solid foundation for system administration and DevOps.
