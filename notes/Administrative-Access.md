# 🔐 Day5 Administrative Access in Linux

## 📖 Overview

Some Linux commands require **administrative (root) privileges** because they access sensitive system files, hardware, or security settings.
Linux protects the system by preventing regular users from running these privileged commands.

---

# 👤 Root User

The **root user** is the administrator of a Linux system.

### ✨ Root User Privileges

- 🔓 Full access to the entire system
- ⚙️ Install and remove software
- 📁 Modify system files
- 👥 Manage users and permissions
- 🛠️ Configure hardware and services

> ⚠️ Be careful when using the root account. Incorrect commands can affect the entire system.

---

# 🔄 The `su` Command

The **`su` (Switch User)** command allows you to temporarily switch to another user account.

By default, it switches to the **root user**.

## 📝 Syntax

```bash
su [OPTIONS] [USERNAME]
```

### ✅ Recommended Login Shell

```bash
su -
```

or

```bash
su -l
```

or

```bash
su --login
```

These options load the complete environment of the new user.

---

## 💻 Example

```bash
sysadmin@localhost:~$ su -
Password:
root@localhost:~#
```

The prompt changes from:

```bash
sysadmin@localhost:~$
```

to

```bash
root@localhost:~#
```

This indicates you are now logged in as the **root user**.

---

## 🚪 Exit Root User

To return to the previous user:

```bash
exit
```

Example:

```bash
root@localhost:~# exit
logout
sysadmin@localhost:~$
```

---

# ⚡ The `sudo` Command

The **`sudo` (Super User Do)** command executes a **single command** with administrator privileges without switching users.

## 📝 Syntax

```bash
sudo [OPTIONS] COMMAND
```

---

## 💻 Example

```bash
sudo ls /root
```

or

```bash
sudo whoami
```

After entering your password, the command runs with administrator privileges.

---

## 👥 Run Command as Another User

```bash
sudo -u username command
```

Example:

```bash
sudo -u sysadmin whoami
```

---

# 🔍 Difference Between `su` and `sudo`

| 🔹 Feature | 👤 `su` | ⚡ `sudo` |
|------------|---------|-----------|
| Switch user | ✅ Yes | ❌ No |
| Creates new shell | ✅ Yes | ❌ No |
| Runs one command | ❌ No | ✅ Yes |
| Requires root password | ✅ Usually | ❌ Uses current user's password |
| More secure | ❌ | ✅ |

---

# 📌 Commands Practiced

```bash
su -
sudo ls /root
sudo whoami
sudo -u sysadmin whoami
exit
```

---

# 💡 Key Learnings

- 🔐 Administrative tasks require **root privileges**.
- 👤 `su` switches to another user and opens a new shell.
- ⚡ `sudo` executes a single command as an administrator.
- 🚪 `exit` returns to the previous user.
- ✅ `sudo` is safer because it grants temporary administrative access.

---

# 📚 Summary

Linux provides **administrative access** through the **`su`** and **`sudo`** commands.

- 👤 Use **`su`** when you need to work as another user for multiple commands.
- ⚡ Use **`sudo`** when you only need to execute a specific command with administrator privileges.

Using **`sudo`** is considered the safer and recommended approach because it minimizes the risk of accidental system changes.

---

⭐ **Day 5 Completed – Administrative Access in Linux**
