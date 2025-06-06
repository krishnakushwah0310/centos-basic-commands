# 📘 CentOS Basic Commands with Descriptions

This guide contains essential **CentOS Linux commands** for beginners, along with easy-to-understand **English explanations**.

---

## 📂 File and Directory Navigation

| Command | Description |
|--------|-------------|
| `pwd` | Print current working directory (shows where you are). |
| `ls` | List files and directories in current location. |
| `ls -l` | List files/directories with details (permissions, size, date). |
| `ls -a` | List all files, including hidden ones. |
| `cd <path>` | Change directory to `<path>`. Example: `cd /home/user` |
| `cd ..` | Move up to parent directory. |
| `mkdir <folder>` | Create a new directory. |
| `rmdir <folder>` | Remove an empty directory. |
| `rm -r <folder>` | Remove a folder and its contents (recursive). |

---

## 📝 File Management

| Command | Description |
|--------|-------------|
| `touch <file>` | Create a new empty file. |
| `cp <source> <destination>` | Copy a file. Use `-r` for directories. |
| `mv <source> <destination>` | Move or rename a file/directory. |
| `rm <file>` | Delete a file. |
| `cat <file>` | Display file content. |
| `nano <file>` | Open file in Nano editor. |
| `vim <file>` | Open file in Vim editor. |
| `echo "text"` | Print text to terminal. |
| `echo "text" > file.txt` | Write (overwrite) text into file. |
| `echo "text" >> file.txt` | Append text to a file. |

---

## 🧰 System & Utility Commands

| Command | Description |
|--------|-------------|
| `clear` | Clear the terminal screen. |
| `whoami` | Show your current user name. |
| `hostname` | Show the system's hostname. |
| `top` | Show running processes (like Task Manager). |
| `df -h` | Show disk space usage in human-readable format. |
| `free -h` | Show memory usage. |
| `uname -r` | Show Linux kernel version. |
| `uptime` | Show how long the system has been running. |

---

## 🔐 User and Permissions

| Command | Description |
|--------|-------------|
| `chmod` | Change file permissions. Example: `chmod 755 file.sh` |
| `chown` | Change file ownership. Example: `chown user:user file.txt` |
| `id` | Show user ID (UID) and group ID (GID). |
| `passwd` | Change the current user’s password. |

---

## 🌐 Network Commands

| Command | Description |
|--------|-------------|
| `ip a` | Show IP addresses of network interfaces. |
| `ping <host>` | Check connectivity with another host. |
| `hostname -I` | Show local IP address. |
| `curl <url>` | Make an HTTP request (test websites/APIs). |
| `wget <url>` | Download files from the internet. |

---

## ✅ Tips

- Use `man <command>` to read the manual page for any command.
- Use `--help` for short usage guide (e.g., `ls --help`).
- Use `Tab` for auto-completion in terminal.
- Use `Up/Down Arrow` keys to navigate command history.

---

> ✍️ This markdown file is beginner-friendly and perfect for Linux learners or those setting up CentOS servers for the first time.

