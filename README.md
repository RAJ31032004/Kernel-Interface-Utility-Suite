# 🐧 Kernel Interface Utility Suite (KIUS)

## 📌 Project Description

Kernel Interface Utility Suite (KIUS) is a system programming project that implements basic Linux commands using native system calls.  
This project demonstrates direct interaction between user-level applications and the Linux kernel by invoking system calls to perform file and directory operations.

---

## 🎯 Aim

To implement standard Linux utility commands using native system calls for efficient low-level interaction with the operating system kernel.

---

## ⚙️ Commands Implemented

| Command | Description |
|---------|-------------|
| catx    | Display file contents |
| cdx     | Change current directory |
| cpx     | Copy contents from one file to another |
| lsx     | List files in current directory |
| mvx     | Move or rename file |
| pwdx    | Display current working directory |
| rmx     | Delete file |
| statx   | Display file metadata and permissions |
| touchx  | Create new file |
| unsmex  | Display system information |

---

## 🛠️ System Calls Used

- open()
- read()
- write()
- close()
- access()
- creat()
- chdir()
- getcwd()
- unlink()
- rename()
- stat()
- opendir()
- readdir()
- closedir()
- uname()

---

## 🖥️ Technologies Used

- Programming Language: C
- Platform: Linux (Ubuntu)
- Concept: System Programming
- API: Linux System Calls

---

## ▶️ Compile Commands

```bash
gcc catx.c -o catx
gcc cdx.c -o cdx
gcc cpx.c -o cpx
gcc lsx.c -o lsx
gcc mvx.c -o mvx
gcc pwdx.c -o pwdx
gcc rmx.c -o rmx
gcc statx.c -o statx
gcc touchx.c -o touchx
gcc unsmex.c -o unsmex
