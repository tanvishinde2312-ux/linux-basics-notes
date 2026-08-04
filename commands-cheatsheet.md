# 📚 Linux Command Cheat Sheet

A quick reference to commonly used Linux commands.

---

# 📂 Navigation Commands

| Command | Description |
|---------|-------------|
| `pwd` | Show current working directory |
| `ls` | List files and directories |
| `ls -l` | Long listing format |
| `ls -a` | Show hidden files |
| `ls -lah` | Long listing with hidden files and human-readable sizes |
| `cd` | Change directory |
| `cd ..` | Move to parent directory |
| `cd ~` | Go to home directory |
| `cd /` | Go to root directory |
| `clear` | Clear the terminal screen |

---

# 📁 File & Directory Management

| Command | Description |
|---------|-------------|
| `mkdir folder` | Create a new directory |
| `mkdir -p dir1/dir2` | Create nested directories |
| `rmdir folder` | Remove an empty directory |
| `rm file` | Delete a file |
| `rm -r folder` | Delete a directory recursively |
| `rm -rf folder` | Force delete directory |
| `cp file1 file2` | Copy a file |
| `cp -r dir1 dir2` | Copy a directory |
| `mv file newname` | Rename a file |
| `mv file folder` | Move a file |
| `touch file.txt` | Create an empty file |

---

# 📄 Viewing File Contents

| Command | Description |
|---------|-------------|
| `cat file.txt` | Display file contents |
| `less file.txt` | View file page by page |
| `more file.txt` | View file page by page |
| `head file.txt` | Show first 10 lines |
| `tail file.txt` | Show last 10 lines |
| `tail -f file.log` | Monitor file updates |

---

# 🔍 Search Commands

| Command | Description |
|---------|-------------|
| `find . -name file.txt` | Search for a file |
| `locate file.txt` | Quickly locate a file |
| `grep "text" file.txt` | Search text inside a file |
| `grep -i "text" file.txt` | Ignore case |
| `grep -r "text" folder` | Search recursively |

---

# 👤 User Commands

| Command | Description |
|---------|-------------|
| `whoami` | Show current user |
| `who` | Display logged-in users |
| `id` | Show user ID and groups |
| `passwd` | Change password |
| `sudo command` | Execute as administrator |

---

# 🔒 Permissions & Ownership

| Command | Description |
|---------|-------------|
| `ls -l` | View permissions |
| `chmod 755 file` | Change permissions |
| `chmod +x file` | Make executable |
| `chown user file` | Change owner |
| `chgrp group file` | Change group |

---

# ⚙️ Process Management

| Command | Description |
|---------|-------------|
| `ps` | View running processes |
| `ps aux` | Detailed process list |
| `top` | Real-time process monitor |
| `kill PID` | Terminate process |
| `kill -9 PID` | Force terminate process |

---

# 🌐 Networking

| Command | Description |
|---------|-------------|
| `ip addr` | Show IP address |
| `hostname` | Display hostname |
| `ping google.com` | Test network connectivity |
| `curl URL` | Fetch webpage |
| `wget URL` | Download files |

---

# 💾 Disk & Storage

| Command | Description |
|---------|-------------|
| `df -h` | Disk usage |
| `du -sh folder` | Folder size |
| `free -h` | Memory usage |
| `lsblk` | List storage devices |

---

# 📦 Package Management (Ubuntu/Debian)

| Command | Description |
|---------|-------------|
| `sudo apt update` | Update package list |
| `sudo apt upgrade` | Upgrade packages |
| `sudo apt install package` | Install package |
| `sudo apt remove package` | Remove package |

---

# 📦 Package Management (RHEL/Fedora)

| Command | Description |
|---------|-------------|
| `sudo dnf install package` | Install package |
| `sudo dnf update` | Update packages |
| `sudo dnf remove package` | Remove package |

---

# 📝 Text Editors

| Command | Description |
|---------|-------------|
| `nano file.txt` | Open Nano editor |
| `vi file.txt` | Open Vim editor |
| `vim file.txt` | Open Vim editor |

---

# 📜 Shell & History

| Command | Description |
|---------|-------------|
| `history` | Show command history |
| `!!` | Repeat previous command |
| `alias ll='ls -lah'` | Create alias |
| `echo $HOME` | Show home directory |
| `echo $PATH` | Show PATH variable |

---

# 📅 System Information

| Command | Description |
|---------|-------------|
| `date` | Display date & time |
| `cal` | Show calendar |
| `uname -a` | System information |
| `hostnamectl` | Host details |
| `uptime` | System uptime |

---

# 💡 Tips

- ✅ Linux commands are **case-sensitive**.
- ✅ Use the **Tab** key for auto-completion.
- ✅ Press **↑** to access previous commands.
- ✅ Use `man <command>` to view the manual.
- ✅ Use `<command> --help` for quick help.

---

## 📚 Based on NDG Linux Unhatched & LPI Linux Essentials (010-160)

This cheat sheet covers the essential Linux commands for beginners and aligns with the **NDG Linux Unhatched** course and **LPI Linux Essentials (010-160)** exam objectives.
