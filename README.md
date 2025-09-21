# 🖥️ Python-Based Command Terminal

A Python-based command terminal that mimics the behavior of a real system terminal.  
This project is built in **Python** and works inside Google Colab or any Python environment.  
It supports file and directory operations, error handling, and system monitoring commands.  

---

## 🚀 Features
- ✅ **File & Directory Operations**
  - `ls` → list files and folders  
  - `cd <directory>` → change directory  
  - `pwd` → print working directory  
  - `mkdir <folder_name>` → create a folder  
  - `rm <file_or_folder>` → remove a file or folder  
  - `cat <file>` → view file content  

- ✅ **System Monitoring**
  - `top` → view CPU usage, memory usage, and first 10 processes  

- ✅ **Other Features**
  - Error handling for invalid commands  
  - Exit with `exit`  
  - Clean and responsive CLI-style interface  

---

## 📂 Example Usage

```bash
/content $ pwd
/content

/content $ ls
sample.txt  demo_folder

/content $ mkdir test
/content $ ls
sample.txt  demo_folder  test

/content $ cd test
/content/test $ pwd
/content/test

/content/test $ cat ../sample.txt
Hello, World!

/content/test $ top
CPU Usage: 12.5%
Memory Usage: 34.8%
Running Processes:
1 - python3 - running
...
