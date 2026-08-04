# 💻 Basic Command Syntax

## 📖 What is a Command?

A **command** is a program that is executed in the **Linux Terminal** to perform a specific task such as listing files, creating folders, or displaying system information.

### 📝 Example
```bash
ls
```

---
## 🛠️ Command Syntax

Most Linux commands follow this format:

```text
command [options] [arguments]
```

---

## ⚙️ Command

The **command** is the main program you want to execute.

### 📝 Example

```bash
ls
```

➡️ Displays the files and directories in the current location.

---

## 📂 Arguments

**Arguments** specify what the command should work on.

### 📝 Example

```bash
ls Documents
```

➡️ Lists the contents of the **Documents** directory.

---

## ⚡ Options

**Options** modify or change the behavior of a command.

### 📝 Example 1

```bash
ls -l
```

➡️ Displays files in **long (detailed) format**.

### 📝 Example 2

```bash
ls -r
```

➡️ Lists files in **reverse alphabetical order**.

### 📝 Example 3

```bash
ls -lr
```

or

```bash
ls -l -r
```

➡️ Both commands produce the **same output** (long listing in reverse order).

---

## 🔠 Case Sensitivity

Linux commands are **case-sensitive**.

### ✅ Correct

```bash
ls
```

### ❌ Incorrect

```bash
LS
```

> 💡 `ls` and `LS` are treated as **different commands**.

---

## 💻 Commands Learned

| 🖥️ Command | 📝 Description |
|------------|----------------|
| `ls` | 📂 List files and directories |
| `ls -l` | 📋 Display detailed file information |
| `ls -r` | 🔄 List files in reverse order |
| `ls -lr` | 📋🔄 Long listing in reverse order |

---

## 📌 Key Takeaways

- ✅ Linux commands are **case-sensitive**.
- 📝 Most commands follow the syntax:
  ```text
  command [options] [arguments]
  ```
- 📂 **Arguments** specify what the command should work on.
- ⚙️ **Options** modify the behavior of commands.
- 🔗 Multiple options can be combined (e.g., `ls -lr`).

---

## 📚 Summary

Understanding **command syntax** is one of the first steps in learning Linux. By combining **commands**, **options**, and **arguments**, you can perform a wide range of tasks efficiently using the Linux terminal.
