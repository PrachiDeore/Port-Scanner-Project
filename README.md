# cybersecurity-project-3

# 🔍 Multi-threaded Python Port Scanner

A simple, fast, and customizable **command-line port scanner** written in Python.  
It uses **multithreading** to scan ports on a target host or domain efficiently and prints open ports along with common service names.

---

## 🚀 Features

- ✅ Multi-threaded scanning (faster!)
- ✅ Custom port range (`-p`)
- ✅ Adjustable number of threads (`-t`)
- ✅ Built-in list of common ports & services
- ✅ Works with IP addresses or domain names

---

## 📦 Requirements

This tool uses only built-in Python libraries:
- `socket`
- `threading`
- `argparse`
- `queue`

✅ No external installations required.

---

## 🛠️ Usage

### 🔧 Run from the terminal:

```bash
python port_scanner.py <target> [options]
