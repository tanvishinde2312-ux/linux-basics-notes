# 📅 Day 8 Practice – File Management

## 🎯 Objective

Practice Linux file management commands to copy, move, rename, and remove files.

---

## Commands Practiced

### Navigate to Documents

```bash
cd ~/Documents
```

---

### Copy a File

```bash
cp /etc/passwd .
```

**Result:** Copied the `passwd` file to the current directory.

---

### Verify the Copy

```bash
ls
```

**Result:** The `passwd` file appeared in the directory listing.

---

### Move a File

```bash
mv people.csv Work
```

**Result:** Moved `people.csv` to the `Work` directory.

---

### Rename a File

```bash
mv animals.txt zoo.txt
```

**Result:** Renamed `animals.txt` to `zoo.txt`.

---

### Remove a File

```bash
rm linux.txt
```

**Result:** Deleted `linux.txt` permanently.

---

### Remove a Directory

```bash
rm -r Work
```

**Result:** Deleted the `Work` directory and its contents.

---

### Create a 50 MB File Using `dd`

```bash
cd ~

dd if=/dev/zero of=/tmp/swapex bs=1M count=50
```

**Result:** Created a 50 MB file filled with zeros.

---

## 📸 Screenshots

- ✅ `cp` command
- ✅ `mv` command
- ✅ `rm` command
- ✅ `dd` command

---

## 📚 Skills Practiced

- File Copying (`cp`)
- File Moving (`mv`)
- File Renaming (`mv`)
- File Deletion (`rm`)
- Directory Deletion (`rm -r`)
- Data Copying (`dd`)

---

## ✅ Status

Completed successfully.
