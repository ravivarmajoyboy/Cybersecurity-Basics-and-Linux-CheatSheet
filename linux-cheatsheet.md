# 🐧 Linux Cheat Sheet

A quick reference for commonly used Linux commands.

---

## 📂 File & Directory Management

| Command | Description |
|---|---|
| `pwd` | Show current directory |
| `ls` | List files |
| `ls -la` | List all files with details |
| `cd dir` | Change directory |
| `cd ..` | Move one level up |
| `mkdir dir` | Create directory |
| `rmdir dir` | Remove empty directory |
| `rm file` | Delete file |
| `rm -r dir` | Delete directory recursively |
| `cp file1 file2` | Copy file |
| `cp -r dir1 dir2` | Copy directory |
| `mv old new` | Move or rename file |

---

## 📄 File Viewing

| Command | Description |
|---|---|
| `cat file` | Show file contents |
| `less file` | View file page by page |
| `head file` | Show first 10 lines |
| `tail file` | Show last 10 lines |
| `tail -f file` | Live log monitoring |

---

## 🔍 Search

| Command | Description |
|---|---|
| `find /path -name file` | Search file by name |
| `grep "text" file` | Search text inside file |
| `grep -r "text" dir` | Search recursively |
| `which command` | Locate command path |

---

## 📦 Package Management (Ubuntu/Debian)

| Command | Description |
|---|---|
| `sudo apt update` | Update package list |
| `sudo apt upgrade` | Upgrade packages |
| `sudo apt install pkg` | Install package |
| `sudo apt remove pkg` | Remove package |

---

## ⚙️ Permissions

| Command | Description |
|---|---|
| `chmod 755 file` | Change file permissions |
| `chown user:group file` | Change ownership |
| `ls -l` | View permissions |

Permission numbers:

```
7 = read + write + execute
6 = read + write
5 = read + execute
4 = read only
```

---

## 🖥️ System Information

| Command | Description |
|---|---|
| `uname -a` | System info |
| `top` | Live process monitor |
| `htop` | Better process monitor |
| `df -h` | Disk usage |
| `free -h` | Memory usage |
| `uptime` | System running time |

---

## 🔌 Networking

| Command | Description |
|---|---|
| `ip a` | Show IP address |
| `ping google.com` | Test connectivity |
| `curl url` | Fetch URL |
| `wget url` | Download file |
| `netstat -tulpn` | Open ports |

---

## 📦 Archive & Compression

| Command | Description |
|---|---|
| `tar -cvf file.tar dir` | Create tar archive |
| `tar -xvf file.tar` | Extract tar archive |
| `tar -czvf file.tar.gz dir` | Create gzip tar |
| `tar -xzvf file.tar.gz` | Extract gzip tar |
| `zip file.zip file` | Create zip |
| `unzip file.zip` | Extract zip |

---

## 🔥 Useful Shortcuts

| Shortcut | Description |
|---|---|
| `Ctrl + C` | Stop command |
| `Ctrl + Z` | Pause process |
| `Ctrl + L` | Clear terminal |
| `Ctrl + A` | Start of line |
| `Ctrl + E` | End of line |

---

## 📜 Process Management

| Command | Description |
|---|---|
| `ps aux` | List running processes |
| `kill PID` | Kill process |
| `kill -9 PID` | Force kill process |
| `jobs` | Show background jobs |
| `bg` | Resume job in background |
| `fg` | Bring job to foreground |