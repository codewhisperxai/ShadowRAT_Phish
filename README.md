# 👤 ShadowRAT_Phish – Advanced Phishing + Android RAT Tool 🔥

A powerful, modular tool that combines **Phishing Page Generation** and **Android RAT Payload Creation**, built for **Kali Linux** and **Termux**. Designed for ethical hacking, red teaming, and cybersecurity education purposes only.

---

## ⚙️ Features

✅ Real Phishing Page Templates  
✅ Android Remote Access Tool (RAT) APK Generator  
✅ Works on Termux & Kali Linux  
✅ Auto Ngrok Tunneling Support  
✅ Full Metasploit Integration  
✅ Modular CLI Interface  
✅ IP Logger, Location Tracker, Camera Access (in modules)  

---

## 📦 Included Components

- `setup.sh` – One-click auto installer  
- `start.sh` – Main launcher with menu  
- `rat_builder.sh` – Android payload generator  
- `phishing/` – Prebuilt login templates (Facebook, Instagram, etc.)  
- `modules/` – Extra payload tools (camera, mic, SMS, location etc.)

---

## 🛠️ Installation

### On Kali Linux / Ubuntu:
```bash
git clone https://github.com/CodeWhishperX/ShadowRAT_Phish
cd ShadowRAT_Phish
bash setup.sh
bash start.sh
````

### On Termux:

```bash
pkg update && pkg upgrade
pkg install git -y
git clone https://github.com/CodeWhishperX/ShadowRAT_Phish
cd ShadowRAT_Phish
bash setup.sh
bash start.sh
```

---

## 🧪 Sample Usage

### 📌 Generate Android RAT:

```bash
bash rat_builder.sh
```

➡️ Enter:

* `LHOST`: Your IP or Ngrok URL
* `LPORT`: Port (default: 4444)

Result: `rat_payload.apk` generated and ready to send.

---

### 🎣 Start Phishing Page:

```bash
cd phishing
bash launch.sh
```

➡️ Choose template (e.g., Facebook, Instagram)
➡️ Choose Ngrok or localhost
➡️ Send link to target
➡️ Credentials saved to `logs/` folder

---

## 📷 Sample Output Screenshot

> ![Sample Output](https://raw.githubusercontent.com/CodeWhishperX/ShadowRAT_Phish/main/assets/demo.png)

---

## ⚠️ Disclaimer

This tool is for **educational and ethical purposes only**.
We are **not responsible** for any misuse.
Always take **legal permission** before testing or deploying on any system.

---

## 👨‍💻 Author

* Tool by: [Code Whishper X](https://github.com/CodeWhishperX)
* Telegram Support: `@codewhishperx`
* For PVT tool - https://wa.me/916009635122?text=Hi%20sir%2C%20I%20want%20to%20buy%20my%20pvt%20tool

---

## 📢 Credits

Inspired by:

* HiddenEye
* ZPhisher
* Metasploit
* Evil-Droid

---

🛡️ Learn | Practice | Defend | Report 
