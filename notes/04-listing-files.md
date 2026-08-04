# 📂 Listing Files in Linux

## 📖 Overview

The **`ls` (List)** command is used to display the contents of a directory. It is one of the most commonly used Linux commands for viewing files and folders.

---

## 🛠️ Syntax

```bash
ls [OPTIONS] [FILE]
```

- ⚙️ **OPTIONS** modify the command's behavior.
- 📂 **FILE** specifies the directory or file to list.

---

## 💻 Basic Command

```bash
ls
```

### 📤 Sample Output

```bash
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos
```

➡️ Displays all files and directories in the current location.

---

# 📋 Long Listing Format

Use the **`-l`** option to display detailed information about files.

### 💻 Command

```bash
ls -l
```

### 📤 Sample Output

```text
drwxr-xr-x 2 sysadmin sysadmin 4096 Dec 20 2017 Documents
-rw-r--r-- 1 sysadmin sysadmin 1024 Oct 10 2025 notes.txt
```

---

# 🔍 Understanding `ls -l` Output

| 🏷️ Field | 📝 Description |
|-----------|----------------|
| 📂 File Type | Directory, file, link, etc. |
| 🔐 Permissions | Read, write and execute permissions |
| 🔗 Hard Links | Number of hard links |
| 👤 Owner | User who owns the file |
| 👥 Group | Group owner |
| 📏 File Size | Size of the file |
| 📅 Timestamp | Last modified date & time |
| 📄 Filename | Name of the file |

---

## 📁 File Types

| 🔣 Symbol | 📄 Type |
|-----------|---------|
| `-` | 📄 Regular File |
| `d` | 📂 Directory |
| `l` | 🔗 Symbolic Link |
| `c` | 💻 Character Device |
| `b` | 💾 Block Device |
| `p` | 🚰 Pipe |
| `s` | 🔌 Socket |

---

# 🔄 Sorting Files

## ⏰ Sort by Last Modified Time

```bash
ls -lt
```

➡️ Displays the newest files first.

---

## 📏 Sort by File Size

```bash
ls -lS
```

➡️ Displays the largest files first.

---

## 🔁 Reverse Sort by File Size

```bash
ls -lSr
```

➡️ Displays the smallest files first.

---

## 🔃 Reverse Alphabetical Order

```bash
ls -r
```

➡️ Lists files in reverse alphabetical order.

---

# 💻 Commands Practiced

```bash
ls
ls -l
ls -r
ls -lt
ls -lS
ls -lSr
```

---

# ⚡ Quick Tips

- 📂 `ls` → List files and folders
- 📋 `ls -l` → Detailed file information
- ⏰ `ls -lt` → Sort by modification time
- 📏 `ls -lS` → Sort by file size
- 🔁 `ls -lSr` → Smallest files first
- 🔃 `ls -r` → Reverse alphabetical order

---

# 📝 Key Learnings

- ✅ Used the `ls` command to view directory contents.
- 📋 Learned how to read detailed file information.
- 📂 Identified different Linux file types.
- 📏 Sorted files by size.
- ⏰ Sorted files by modification time.
- 🔄 Used reverse sorting options.

---

# 📚 Summary

The **`ls`** command is an essential Linux command used to view, organize, and analyze files and directories. By combining different options such as **`-l`**, **`-t`**, **`-S`**, and **`-r`**, you can display file information in multiple useful ways, making file management faster and more efficient.

---

⭐ **Day 4 Complete – Listing Files (`ls`)**
