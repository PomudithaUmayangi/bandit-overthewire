# 🏴‍☠️ Bandit OverTheWire Walkthrough

## 📖 Project Overview

The **Bandit** wargame from **OverTheWire** is designed to help beginners get comfortable with the Linux command line and security principles.  
This repository provides a **detailed walkthrough** for all levels, covering essential Linux commands, file manipulation, and privilege escalation techniques.

---

## 💡 Key Highlights:
- Learn **Linux basics**, **file permissions**, and **networking commands**.
- Use **SSH**, **find hidden files**, and **decode passwords** at each level.
- Improve your **cybersecurity skills** by solving real-world security challenges.

---

## 🛠️ Features and Implementations

### 1️⃣ **Challenges Covered**
- **Level 0 to Level 20**:  
  - **Connecting via SSH** and navigating the system.  
  - **Reading hidden files**, **handling tricky filenames**, and **decoding passwords**.  
  - **Using Linux tools** like `ls`, `cat`, `grep`, `find`, `strings`, and `base64`.  
  - **Extracting data from compressed files** (`tar`, `gzip`, `bzip2`).  
  - **Privilege escalation** using `nmap`, `nc`, and `cron jobs`.

---

### 2️⃣ **Security Tools & Commands**
- **SSH**: Securely access remote machines.
- **`ls`, `cd`, `cat`, `find`**: Navigate the filesystem and locate passwords.
- **`strings`, `grep`, `sort`, `uniq`**: Extract useful data from files.
- **`base64`, `tr`, `xxd`**: Encode/decode and analyze binary files.
- **`tar`, `gzip`, `bzip2`**: Work with compressed archives.
- **`nmap`, `netcat (nc)`**: Scan ports and interact with network services.

---

## 🔒 Key Takeaways

### 🔹 **Linux Security Concepts**
- **File Permissions**: Understand **read/write/execute** permissions and ownership.
- **Hidden Files & Directories**: Learn how attackers **hide data** in unusual locations.
- **Encoded & Encrypted Data**: Use **decoding tools** to retrieve hidden messages.
- **Network Services & Ports**: Scan and interact with open ports to retrieve information.

---

## 📂 Files Included
- 📄 `bandit_overthewire.pdf` - A step-by-step guide covering all levels.
- 📜 `README.md` - This documentation file.

---

## 🚀 Getting Started  

### 🔗 **Play Bandit on OverTheWire**
1️⃣ Open a terminal.  
2️⃣ Connect to the Bandit server using SSH:  
   ```sh
   ssh bandit0@bandit.labs.overthewire.org -p 2220
