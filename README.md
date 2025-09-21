
# 🔐 File Integrity Checker  

A Python-based tool to detect file tampering by generating and comparing **SHA-256 hashes**.  
It helps identify whether files are **modified, missing, or newly added**, with results stored in an SQLite database for tracking.  

## ⚡ Features  
- Generates and stores **SHA-256 hash values** of files  
- Detects changes by comparing new hashes with stored values  
- Flags **tampered, missing, or new files**  
- Maintains history using an **SQLite database**  
- Simple **command-line interface** for ease of use  

## 🛠️ Tech Stack  
- **Language:** Python  
- **Database:** SQLite  
- **Libraries:** hashlib, sqlite3, os  

