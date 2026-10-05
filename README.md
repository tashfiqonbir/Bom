# Bom
Use only for education purpose 
# 🚀 SMS/Call Bomber Tool Created by "Tashfiq Onbir"

A powerful and multi-threaded SMS/Call flooding utility built with Python for testing and educational purposes. 

> [!WARNING]
> **Disclaimer:** This tool is strictly for educational and authorized testing purposes only. The author is not responsible for any misuse or damage caused by this program.

---

## ✨ Features
- **Asynchronous Requests:** Powered by `aiohttp` for lightning-fast concurrent operations.
- **Robust HTTP Handling:** Utilizes `urllib3` for stable connection pooling and request management.
- **Base64 Obfuscated Core:** Clean backend logic designed for optimal performance.
- **Easy Termux & Linux Setup:** Quick deployment on mobile (Termux) and desktop environments.

---

## 📋 Prerequisites

Before running the tool, make sure you have **Python 3.x** and `pip` installed.

### For Linux / macOS:
```bash
python3 --version
pip3 --version
```

### For Termux (Android):
Ensure your packages are up-to-date and the required repository hooks are installed:
```bash
pkg update && pkg upgrade -y
pkg install python -y
pkg install tur-repo -y
```

---

## ⚙️ Installation & Setup

Follow these simple steps to install the required dependencies and run the project:

### 1. Clone the Repository
```bash
git clone https://github.com/tashfiqonbir/bom
cd Bom
```

### 2. Install Dependencies
This project relies on external Python modules (`aiohttp` and `urllib3`). Install them directly via `pip`:
```bash
pip install aiohttp urllib3
```
*Note for Termux users: If pip compilation fails, you can install pre-compiled packages using:*
```bash
pkg install python-aiohttp python-urllib3
```

### 3. Run the Tool
Once all dependencies are successfully installed, execute the main script:
```bash
python bom.py
```

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com) if you want to report any bugs or suggest new features.

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).
