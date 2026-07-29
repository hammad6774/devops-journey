**Linux Commands**


**Day 1: Linux Basics & Commands**


### 🔹 Navigation & Directories
| Command | Description | Example |
|---------|-------------|---------|
| `pwd`   | Show current working directory | `pwd` |
| `ls`    | List files/folders | `ls -l` |
| `ls -R` | List files recursively | `ls -R /home` |
| `cd <dir>` | Change directory | `cd Documents` |
| `cd ..` | Go up one directory | `cd ..` |
| `cd -`  | Go to previous directory | `cd -` |

---

### 🔹 File & Directory Management
| Command | Description | Example |
|---------|-------------|---------|
| `touch file.txt` | Create empty file | `touch notes.txt` |
| `mkdir folder` | Create directory | `mkdir projects` |
| `mkdir -p a/b/c` | Create nested directories | `mkdir -p dev/linux/day1` |
| `mv file1 file2` | Move or rename file | `mv old.txt new.txt` |
| `cp file1 file2` | Copy file | `cp file.txt copy.txt` |
| `cp -r dir1 dir2` | Copy directory recursively | `cp -r src backup` |
| `rm file.txt` | Delete file | `rm notes.txt` |
| `rm -r folder` | Delete directory recursively | `rm -r temp` |

---

### 🔹 Viewing & Reading Files
| Command | Description | Example |
|---------|-------------|---------|
| `cat file.txt` | View contents | `cat notes.txt` |
| `head -n 5 file.txt` | Show first 5 lines | `head -n 5 log.txt` |
| `wc file.txt` | Word/line/char count | `wc notes.txt` |

---

### 🔹 Help & Info
| Command | Description | Example |
|---------|-------------|---------|
| `whatis command` | One-line description | `whatis ls` |
| `man command` | Manual/help page | `man ls` |

---

### 🔹 History & Search
| Command | Description | Example |
|---------|-------------|---------|
| `history` | Show previously used commands | `history` |
| `ctrl+R` | Reverse search through history | (press `ctrl+R` and type `ls`) |

---

### 🔹 Pipes & Redirection
| Symbol | Description | Example |
|--------|-------------|---------|
| `|` | Pipe output into another command | `ls | grep txt` |
| `>` | Redirect output (overwrite file) | `ls > files.txt` |
| `>>` | Append output to file | `echo "Hi" >> notes.txt` |

---

### 🔹 Searching
| Command | Description | Example |
|---------|-------------|---------|
| `grep "word" file.txt` | Search for text in file | `grep "error" log.txt` |

---

### ✅ Today I Learned
- How to navigate directories (`cd`, `pwd`, `ls`, etc.).  
- How to create, copy, move, and remove files/folders.  
- How to view and search inside files using `cat`, `head`, and `grep`.  
- How to use history (`history`, `ctrl+R`) to save time.  
- How to use pipes (`|`) and redirection (`>`, `>>`) for command chaining.  

---
