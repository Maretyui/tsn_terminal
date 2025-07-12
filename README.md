# 🧠 TrueSilveredNightmare (TSN)

**TrueSilveredNightmare (TSN)** is a Python-based Remote Access Tool (RAT) developed for **ethical hacking** demonstrations and **educational purposes only**. It enables a locally hosted server to interact with a client (distributed as an executable `.exe`), which is controlled via a clean web-based frontend:

🌐 **Frontend URL**: [https://maretyui.com/virus/](https://maretyui.com/virus/)

> ⚠️ Use responsibly. This project is intended solely for ethical cybersecurity learning in **controlled environments**.

---

## 📦 Features

- ✅ Python-built client compiled into a `.exe`
- ✅ Locally hosted server backend
- ✅ Clean, web-based frontend interface
- ✅ One-to-many client control demonstration
- ✅ Useful for Red Team/Blue Team education
- ✅ Easy to configure and deploy in labs

---

## 🚀 Getting Started

> ⚠️ You must have **explicit permission** to run TSN on any device that you do not personally own.

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/TrueSilveredNightmare.git
cd TrueSilveredNightmare
```

### 2. Server Setup

Navigate to the server folder and install dependencies:

```bash
cd server
pip install -r requirements.txt
```

Start the server:

```bash
python server.py
```

This will begin listening for incoming connections from the client executable.

### 3. Build the Client Executable

Navigate to the `client` directory:

```bash
cd ../client
```

Install `pyinstaller` (if not already installed):

```bash
pip install pyinstaller
```

Then compile the client:

```bash
pyinstaller --onefile client.py
```

The `.exe` file will be located in the `dist/` folder.

> ⚠️ **Run this executable only on devices you own or have written permission to test.**

---

## 🌐 Frontend Access

The frontend dashboard to manage and monitor connections is available at:

🔗 **[https://maretyui.com/virus/](https://maretyui.com/virus/)**

You can log in and interact with connected clients through this secure interface.

---

## ⚖️ Legal Disclaimer

**TSN is strictly for educational, ethical, and legal use only.**

By using this software, you agree to the following terms:

- You will **only use TSN** on systems you **own** or have been **explicitly authorized** to test.
- You understand that **unauthorized access to computer systems is illegal** and can result in severe criminal charges.
- You are fully responsible for any misuse or illegal actions taken using this tool.

**We disclaim all liability for damage, legal issues, or misuse.**

This software is distributed with the good faith that it will be used to **promote learning**, **cybersecurity awareness**, and **defensive security practices**.

---

## 🛠️ Contribution

We welcome ethical contributions! To contribute:

1. Fork the repository  
2. Create your feature branch  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m 'Add YourFeature'
   ```
4. Push to the branch  
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

> **Educational Purpose Only – Not for Malicious Use**
