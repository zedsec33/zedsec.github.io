# 🧠 ZedSec Reverse Shell Suite

This project showcases a custom reverse shell written in Python for red team operations, C2 testing, and malware lab development.

## ⚔️ Purpose

This shell is built for:

- Payload chaining in internal lab simulations
- Command & Control (C2) development
- Penetration testing and adversary emulation
- Ethical red teaming environments

## 💻 Features

- Reverse TCP shell over socket
- Graceful exit handling
- Cross-platform compatible
- Minimal dependencies

## 🧪 Tested In

- Arch Linux / Kali Linux
- Windows 10 (x86/x64) via VirtualBox
- Host-only networks

## 🚀 Usage

1. **Start listener on attacker machine:**
   ```bash
   nc -lvnp 4444
   ```

2. **Deploy on victim (lab only):**
   ```bash
   python reverse_shell.py
   ```

## 📂 Structure

```
.
├── reverse_shell.py   # Python-based reverse shell
├── README.md
├── LICENSE
└── screenshots/
```

## 📸 Screenshots

<img src="screenshots/demo.png" alt="Reverse Shell Demo" width="600"/>

## 🔐 Legal Disclaimer

For ethical hacking in **controlled, lab-based environments** only.  
ZedSec does not condone unauthorized access or malicious use.

## 📫 Contact

Made by ZedSec — Solo Red Team Operator  
📧 hacktheworld.zedsec@yahoo.com
"""

