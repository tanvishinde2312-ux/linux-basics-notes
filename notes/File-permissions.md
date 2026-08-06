# 🔐 File Permissions in Linux

## 📖 Overview

File permissions control **who can read, write, or execute** a file or directory. They help protect files from unauthorized access and modifications.

---

# 📂 Viewing Permissions

Use the `ls -l` command to display file permissions.

## 💻 Syntax

```bash
ls -l
```

### Example

```bash
ls -l hello.sh
```

Output:

```bash
-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20 2017 hello.sh
```

---

# 📋 Permission Structure

```text
-rwxr-xr--
││ │ │
││ │ └── Others
││ └──── Group
│└────── Owner
└──────── File Type
```

---

# 📁 File Types

| 🔹 Symbol | 📄 Type |
|-----------|----------|
| `-` | Regular File |
| `d` | Directory |
| `l` | Symbolic Link |

---

# 👥 Permission Groups

| 👤 Group | 📝 Description |
|----------|----------------|
| `u` | Owner (User) |
| `g` | Group |
| `o` | Others |
| `a` | All Users |

---

# 🔑 Permission Types

| Symbol | Permission | Description |
|--------|------------|-------------|
| `r` | Read | View file contents |
| `w` | Write | Modify file |
| `x` | Execute | Run a file or access a directory |

---

# ⚙️ Changing Permissions

The **`chmod`** command changes file permissions.

## 📝 Syntax

```bash
chmod [OPTIONS] MODE FILE
```

---

## ➕ Add Execute Permission

```bash
chmod u+x hello.sh
```

Gives execute permission to the file owner.

---

## ➖ Remove Execute Permission

```bash
chmod u-x hello.sh
```

Removes execute permission.

---

## 🟰 Set Exact Permission

```bash
chmod u=rwx hello.sh
```

Sets the owner's permissions to **read, write, and execute**.

---

# ▶️ Execute a Script

Before execution:

```bash
./hello.sh
```

If execute permission is missing:

```text
Permission denied
```

After adding execute permission:

```bash
chmod u+x hello.sh
./hello.sh
```

Output:

```text
Hello World!
```

---

# 💡 Symbolic Method

## Permission Sets

| Symbol | Meaning |
|--------|---------|
| `u` | User |
| `g` | Group |
| `o` | Others |
| `a` | All |

## Actions

| Symbol | Meaning |
|--------|---------|
| `+` | Add Permission |
| `-` | Remove Permission |
| `=` | Set Exact Permission |

---

# 📌 Commands Practiced

```bash
ls -l
chmod u+x hello.sh
chmod u-x hello.sh
chmod u=rwx hello.sh
./hello.sh
```

---

# ✅ Key Learnings

- 🔐 Linux uses permissions to secure files.
- 👤 Permissions are divided into **Owner, Group, and Others**.
- 📖 The three permissions are **Read, Write, and Execute**.
- ⚙️ `chmod` changes file permissions.
- ▶️ A script needs execute (`x`) permission before it can run.

---

# 📚 Summary

Linux file permissions provide security by controlling access to files and directories. The `chmod` command allows owners or administrators to modify permissions using the symbolic method.

---

⭐ **Day 6 Completed – File Permissions**
