# 📚 Linux Command Cheat Sheet

A quick reference to commonly used Linux commands.

# 📋 Day 1 Command Sheet

| 💻 Command | 📌 Purpose |
|------------|-----------|
| `pwd` | 📂 Show the current working directory |
| `ls` | 📁 List files and directories |
| `whoami` | 👤 Display the current logged-in user |
| `date` | 📅 Show the current system date and time |

---
## 💻 Day 2 Basic Command Syntax

| 🖥️ Command | 📝 Description |
|------------|----------------|
| `ls` | 📂 List files and directories |
| `ls -l` | 📋 Display files in long listing format |
| `ls -r` | 🔄 List files in reverse order |
| `ls -lr` | 📋🔄 Display a long listing in reverse order |
| `ls Documents` | 📁 List the contents of the **Documents** directory |

---
## 📂 Day 3 Directory Navigation

| 🖥️ Command | 📝 Description |
|------------|----------------|
| `pwd` | 📍 Show the current working directory |
| `cd directory` | 📂 Change to the specified directory |
| `cd /` | 🌳 Go to the root directory |
| `cd ~` | 🏠 Go to the home directory |
| `cd ..` | ⬆️ Move to the parent directory |
| `cd .` | 📍 Stay in the current directory |

---
## 📂 Day 4 Listing Files Commands

| 💻 Command | 📝 Description |
|------------|----------------|
| `ls` | 📂 List files and directories |
| `ls directory` | 📁 List contents of a specific directory |
| `ls -l` | 📋 Display detailed (long) listing |
| `ls -r` | 🔄 List files in reverse alphabetical order |
| `ls -lt` | ⏰ Sort files by last modified time (newest first) |
| `ls -lS` | 📏 Sort files by file size (largest first) |
| `ls -lSr` | 🔁 Sort files by file size (smallest first) |

---

## 📋 `ls -l` Output Fields

| 🏷️ Field | 📝 Description |
|-----------|----------------|
| 📂 File Type | Indicates file or directory type |
| 🔐 Permissions | Read, write, and execute permissions |
| 🔗 Hard Links | Number of hard links |
| 👤 Owner | File owner |
| 👥 Group | Group owner |
| 📏 Size | File size |
| 📅 Timestamp | Last modified date & time |
| 📄 Filename | Name of the file |

---

## 📁 Linux File Types

| 🔣 Symbol | 📄 Type |
|-----------|---------|
| `d` | 📂 Directory |
| `-` | 📄 Regular File |
| `l` | 🔗 Symbolic Link |
| `b` | 💾 Block Device |
| `c` | ⌨️ Character Device |
| `p` | 🚰 Pipe |
| `s` | 🔌 Socket |

---

# 🔐Day 5 Administrative Access

| 💻 Command | 📝 Description |
|------------|----------------|
| `su -` | 👤 Switch to the root user (login shell) |
| `su -l` | 🔄 Switch to the root user with a login shell |
| `su --login` | 🔑 Login as another user with a full environment |
| `sudo command` | ⚡ Run a command with administrator privileges |
| `sudo -u username command` | 👥 Run a command as another user |
| `sudo whoami` | 👤 Display the current user after using `sudo` |
| `sudo ls /root` | 📂 List files in the root user's directory |
| `exit` | 🚪 Exit the current shell and return to the previous user |

---

# 🔐Day 6 File Permissions

| 💻 Command | 📝 Description |
|------------|----------------|
| `ls -l` | 📋 Display detailed file permissions |
| `chmod u+x file` | ➕ Add execute permission for the owner |
| `chmod u-x file` | ➖ Remove execute permission for the owner |
| `chmod u=rwx file` | ⚙️ Set read, write, and execute permissions for the owner |
| `./file` | ▶️ Execute a file or script from the current directory |
| `cd ~/Documents` | 📂 Navigate to the Documents directory |

---

# 📑 Day 7 Command Cheat Sheet

| 💻 Command | 📝 Description |
|------------|----------------|
| `cd ~/Documents` | 📂 Go to the Documents directory |
| `ls -l` | 📋 Display detailed file information |
| `sudo chown root hello.sh` | 👑 Change the file owner to **root** |
| `ls -l hello.sh` | 🔍 Verify the updated file ownership |
| `cat animals.txt` | 🐱 Display the entire contents of a file |
| `cat alpha.txt` | 📄 View all lines in a text file |
| `head alpha.txt` | ⬆️ Show the first 10 lines |
| `tail alpha.txt` | ⬇️ Show the last 10 lines |
| `head -n 5 alpha.txt` | 🔢 Display the first 5 lines |
| `tail -n 5 alpha.txt` | 🔢 Display the last 5 lines |

---

# 📑 Day 8 File Management

# 📂 Copying Files (`cp`)
> 📌 **Purpose:** Create a copy of files or directories without modifying the original.

| 🖥️ Command | 📝 Description | 💡 Example |
|:-----------|:---------------|:-----------|
| `cp SOURCE DESTINATION` | Copy a file | `cp file.txt backup.txt` |
| `cp /etc/passwd .` | Copy a file to the current directory | `cp /etc/passwd .` |
| `cp -r DIRECTORY DESTINATION` | Copy an entire directory | `cp -r Project Backup/` |
| `cp file1 file2 DIRECTORY` | Copy multiple files | `cp report.txt notes.txt Backup/` |

> ✅ **Tip:** Use `-r` when copying directories.
---

# 🚚 Moving & Renaming Files (`mv`)
> 📌 **Purpose:** Move files/directories or rename them.

| 🖥️ Command | 📝 Description | 💡 Example |
|:-----------|:---------------|:-----------|
| `mv SOURCE DESTINATION` | Move a file | `mv people.csv Work/` |
| `mv oldname.txt newname.txt` | Rename a file | `mv animals.txt zoo.txt` |
| `mv file1 file2 DIRECTORY` | Move multiple files | `mv notes.txt report.txt Documents/` |
| `mv DIRECTORY DESTINATION` | Move a directory | `mv Project Backup/` |

> ✅ **Tip:** `mv` can **move** and **rename** files using the same command.
---

# 🗑️ Removing Files (`rm`)
> 📌 **Purpose:** Permanently delete files and directories.

| 🖥️ Command | 📝 Description | 💡 Example |
|:-----------|:---------------|:-----------|
| `rm FILE` | Delete a file | `rm linux.txt` |
| `rm -r DIRECTORY` | Delete a directory recursively | `rm -r Work` |
| `rm -rf DIRECTORY` | Force delete a directory | `rm -rf Project` |
| `rm *.txt` | Delete all `.txt` files | `rm *.txt` |

> ⚠️ **Warning:** Files removed using `rm` are **permanently deleted** and cannot be recovered from the Recycle Bin.
---
