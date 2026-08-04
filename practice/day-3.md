# 📂 Directory Navigation in Linux

## 📖 Overview

🐧 Linux organizes files and folders using a **hierarchical file system**. Directories help keep files organized and make navigation easier.

---

## 📍 `pwd` Command

The **`pwd` (Print Working Directory)** command displays your **current working directory**.

### 🛠️ Syntax

```bash
pwd
```

### 💻 Example

```bash
pwd
```

### 📤 Output

```bash
/home/sysadmin
```

✅ Displays the current working directory.

---

## 📁 `cd` Command

The **`cd` (Change Directory)** command is used to move between directories.

### 🛠️ Syntax

```bash
cd [directory]
```

### 💻 Examples

📂 **Go to Documents**

```bash
cd Documents
```

🏠 **Go to Home Directory**

```bash
cd ~
```

🌳 **Go to Root Directory**

```bash
cd /
```

---

## 🌍 Absolute Path

➡️ An **absolute path** always starts from the **root directory (`/`)**.

### 💻 Example

```bash
cd /home/sysadmin
```

---

## 📌 Relative Path

➡️ A **relative path** starts from the **current working directory**.

### 💻 Example

```bash
cd School/Art
```

---

## ⚡ Useful Shortcuts

| 🔖 Shortcut | 📖 Meaning |
|------------|------------|
| `.` | 📍 Current directory |
| `..` | ⬆️ Parent directory |
| `~` | 🏠 Home directory |
| `/` | 🌳 Root directory |

---

## 💻 Commands Practiced

```bash
pwd
cd Documents
cd /
cd /home/sysadmin
cd School/Art
cd ..
cd ~
```

---

## 📝 Key Learnings

- ✅ Used **`pwd`** to view the current directory.
- 📂 Navigated between directories using **`cd`**.
- 🌍 Understood the difference between **absolute** and **relative** paths.
- ⚡ Used shortcuts (`.`, `..`, `~`, `/`) for faster navigation.
- 💡 Learned that the terminal prompt updates automatically after changing directories.

---

## 🚀 Quick Tips

- 📍 Use `pwd` whenever you're unsure of your current location.
- 🏠 `cd ~` instantly takes you to your home directory.
- ⬆️ `cd ..` moves one level up.
- 🌳 `cd /` takes you to the root directory.

---

## 📚 Summary

🎯 The **`pwd`** and **`cd`** commands are essential for navigating the Linux file system. Mastering these commands makes working in the terminal faster, easier, and more efficient.
