# 📂 Directory Navigation in Linux

## 📖 Overview

Linux organizes files and folders using a **hierarchical file system**. Directories help keep files organized, making them easy to locate and manage.

---

## 📍 `pwd` Command

The **`pwd` (Print Working Directory)** command displays your **current directory**.

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

➡️ Displays the current working directory.

---

## 📁 `cd` Command

The **`cd` (Change Directory)** command is used to move between directories.

### 🛠️ Syntax

```bash
cd [directory]
```

### 💻 Examples

#### 📂 Go to Documents

```bash
cd Documents
```

#### 🏠 Go to Home Directory

```bash
cd ~
```

#### 🌳 Go to Root Directory

```bash
cd /
```

---

## 🌍 Absolute Path

An **absolute path** always starts from the **root directory (`/`)**.

### 💻 Example

```bash
cd /home/sysadmin
```

➡️ Starts from the root directory.

---

## 📌 Relative Path

A **relative path** starts from the **current working directory**.

### 💻 Example

```bash
cd School/Art
```

➡️ Starts from your current location.

---

## ⚡ Useful Shortcuts

| 🔖 Shortcut | 📝 Meaning |
|-------------|-----------|
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

## 🎓 Key Learnings

- ✅ Used **`pwd`** to check the current directory.
- 📂 Navigated directories using **`cd`**.
- 🌍 Learned the difference between **absolute** and **relative** paths.
- ⚡ Used shortcuts (`.`, `..`, `~`, `/`) for faster navigation.

---

## 📚 Summary

Understanding **directory navigation** is essential for working efficiently in Linux. The **`pwd`** and **`cd`** commands help you identify your current location and move through the file system with ease.
